pipeline {
    agent any
   
    stages {
        stage('Build') {
            steps {
                bat "mvn package -DskipTest"
                
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying to tomcat"
            }
        }
        
    }
}