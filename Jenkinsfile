pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                // Contoh: sh 'npm test'
                sh 'echo "Running Tests"'
            }
        }
        stage('Lint') {
            steps {
                // Contoh: sh 'npm run lint'
                sh 'echo "Linting Code"'
            }
        }
        stage('Report') {
            steps {
                sh 'echo "Generating Reports"'
            }
        }
    }
}
