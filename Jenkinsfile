pipeline {
    agent any
    stages {
        stage('click') {
            steps {
                sh 'ls -la'
            }
        }
        stage('Test') {
            steps {
                sh 'make test'
            }
        }
    }
}
