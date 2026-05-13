pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Building payment-service..." && sleep 2'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Testing payment-service..." && sleep 3'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying payment-service to staging..." && sleep 1'
            }
        }
    }
}
// Changes for develop
