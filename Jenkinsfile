pipeline {
    agent any

    tools {
        nodejs "NodeJS 12" // Use the name you set in the global tool configuration
    }

    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running Tests"'
                // Uncomment and modify the next line if you have actual tests to run
                // sh 'npm test'
            }
        }
        stage('Lint') {
            steps {
                sh 'echo "Linting Code"'
                // Uncomment and modify the next line if you have linting setup
                // sh 'npm run lint'
            }
        }
        stage('Report') {
            steps {
                sh 'echo "Generating Reports"'
                // Add commands here to generate reports if needed
            }
        }
    }
}
