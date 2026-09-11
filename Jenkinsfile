pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Task: Compile and package the application'
                echo 'Tool: Vite. It is a fast build tool that compiles and bundles the application code, and supports modern frontend frameworks (React, Vue, etc).'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Task: Run unit and API integration tests'
                echo 'Tool: Jest. It is a fast, zero-configuration testing framework with built-in assertion and mocking tools for JavaScript.'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Task: Perform static code analysis and quality checks'
                echo 'Tool: SonarQube. It automatically detect bugs and security issues, and integrates easily in our CI/CD pipeline.'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Task: Scan dependencies for known security vulnerabilities'
                echo 'Tool: Snyk. It extends coverage to open-source dependencies and suggests actionable fixes.'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Task: Deploy application to a staging server'
                echo 'Tool: AWS EC2 deployment using Terraform. It provides isolated cloud virtual servers to safely test application deployments in a production-like environment.'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Task: Run end-to-end tests against the live staging environment'
                echo 'Tool: Cypress. It simulates real user interactions in the browser to verify complete user workflows before release.'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Task: Deploy application to the live production server'
                echo 'Tool: AWS EC2 deployment using Terraform. It delivers scalable, reliable cloud compute capacity to serve end users with high availability.'
            }
        }
    }
}
