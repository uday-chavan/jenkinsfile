pipeline {
    agent any

    environment {
        APP_NAME = "demo-app"
    }

    stages {
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

