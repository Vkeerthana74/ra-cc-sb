pipeline {
    agent any
   
    stages {
        stage('Build') {
            steps {
                bat "mvn package "
                
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying to tomcat"
            }
        }
        
    }
}