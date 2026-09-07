pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Task: Compile and bundle application using npm run build'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Task: Run unit and integration tests (e.g. Jest))'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Task: Static code analysis and linting '
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Task: Scan dependencies for security vulnerabilities using npm audit'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Task: Deploy application to staging server on AWS EC2'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Task: Run end-to-end integration tests on staging (e.g. Cypress)'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Task: Deploy application to production server on AWS EC2'
            }
        }
    }
}
