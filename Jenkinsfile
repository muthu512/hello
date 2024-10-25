pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    bat 'mvn clean package -Dmaven.test.skip=true'
                }
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Add your deployment steps here, e.g., starting the Spring Boot application
            }
        }
    }
}
