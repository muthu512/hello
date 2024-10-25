pipeline {
    agent any 
    tools {
        maven 'Maven 3.9.9' // This should match the name in your configuration
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package -Dmaven.test.skip=true'
            }
        }
    }
}
