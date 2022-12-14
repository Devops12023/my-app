pipeline {
  agent { 
    label 'Ashok'
    }
  tools {
    maven 'maven'
   }
   stages {
     stage ("Run unit test cases") {
          steps {
            script{
              sh """
                cd my-app 
                mvn test """
            }
         }
     }
     
   }
}
