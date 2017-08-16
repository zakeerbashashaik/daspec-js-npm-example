pipeline {
    agent any
    tools {
        maven 'maven-3.5.0'
    }
    stages {
            
        stage ('installation') {
            steps {
                sh 'npm install'
                
            }
          
        }

          stage ('Testing') {
            steps {
               sh 'npm test'
            }
          
        }
    }
}
