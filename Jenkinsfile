pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh '''
                mkdir -p target
                echo "demo jar" > target/demo-app.jar
                '''
            }
        }
    }

    post {
        success {
            archiveArtifacts artifacts: '**/*.jar', fingerprint: true
        }
    }
}
