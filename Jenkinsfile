pipeline {
  agent any 
  stages('Build the app using gradle'){
    stage { 
      steps {
        echo 'Creating a gradle build of the file'
           sh "./gradlew build --no-daemon"
       }
     }
   }
 } 
