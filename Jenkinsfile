pipeline {
    agent any
    tools {
        maven 'Maven3.9.9'  // Ensure this matches the name in Global Tool Configuration
    }
    stages {
        stage('Build') {
            steps {
                bat 'mvn package'
                
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying to tomcat"
            }
        }
        
    }
}
