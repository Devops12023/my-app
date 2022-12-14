pipeline {
  agent { 
    label 'Ashok'
    }
  tools {
    maven 'maven'
   }
   stages {
     stage ("Run unit test cases") {
       script {
         sh """
         cd myapp 
         mvn test """
       }
     }
     stage
   }
}
