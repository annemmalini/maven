pipeline {
    agent any
    stages {
        stage('Checkout the code') {
            steps {
                git 'https://github.com/annemmalini/maven.git'
               
            }
        }
         stage('Build') {
            steps {
              sh 'mvn clean package'
            }
        }
    }
}
    
  
        
     
