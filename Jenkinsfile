pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building Docker Image...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing Application...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to Kubernetes...'
            }
        }
    }
}
