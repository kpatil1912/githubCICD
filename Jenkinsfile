pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout the code
                checkout scm
            }
        }
        stage('Build') {
            steps {
                // Example build step (not really needed for HTML)
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                // Example test step
                echo 'Running tests...'
                // In real projects, you could run test scripts here
            }
        }
        stage('Deploy') {
            steps {
                // Deploy to a server or a static site host
                echo 'Deploying...'
                // You could use a script or command to copy files to a server
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed.'
        }
    }
}
