pipeline {
  agent { 
    label 'Ashok'
    }
  tools {
    maven 'maven'
   }
   stages {
     stage ("Run unit test") {
       script {
         sh " mvn test "
       }
     }
   }
}
