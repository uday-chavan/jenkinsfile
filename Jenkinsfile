pipeline {
    agent any
    environment {
        APP_NAME = "demo-app"
    }
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/username/repo.git'
            }
        }
        stage('Build') {
            steps {
                echo "Building $APP_NAME"
            }
        }
        stage('Test') {
            steps {
                echo "Running tests"
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying application"
            }
        }
    }
}
