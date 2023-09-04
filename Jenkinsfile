pipeline {
    agent {label 'java slave'}
    stages {
        stage('Checkout') {
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
    
  
        
     
