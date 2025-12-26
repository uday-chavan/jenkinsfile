pipeline {
    agent any

    environment {
        ENV = "dev"
        VERSION = "1.0"
    }

    stages {
        stage('Show Env') {
            steps {
                sh '''
                env
                echo "ENV=$ENV"
                echo "VERSION=$VERSION"
                '''
            }
        }
    }
}

