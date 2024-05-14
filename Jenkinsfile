pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Build your application
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                // Run tests
                sh 'npm test'
            }
        }
        stage('Deploy') {
            steps {
                // Deploy your application
                sh 'docker-compose up -d'
            }
        }
    }
}
