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
                cd myapp 
                mvn test """
            }
         }
     }
     
   }
}
