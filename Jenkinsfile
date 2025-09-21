pipeline {
    agent any

    environment {
        GITHUB_REPO = 'placeholder-repo'
        GITHUB_BRANCH = 'main'
    }

    stages {
        stage('Stage 1: Build') {
            steps {
                echo "Building application Using Docker"
            }
        }

        stage('Stage 2: Unit and Integration Tests') {
            steps {
                echo "Running Unit Tests"
            }
        }

        stage('Stage 3: Code Analysis') {
            steps {
                echo "Running Code Analysis"
            }
        }

        stage('Stage 4: Security Scan') {
            steps {
                echo "Running Security Scan"
            }
        }

        stage('Stage 5: Deploy to Staging') {
            steps {
                echo "Deploying to Staging"
            }
        }

        stage('Stage 6: Integration Tests on Staging') {
            steps {
                echo "Running Integration Tests on Staging"
            }
        }

        stage('Stage 7: Deploy to Production') {
            steps {
                echo "Deploying to Production"
            }
        }
    }
}