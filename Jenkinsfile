pipeline {
    agent any
    stages {
        stage('click') {
            steps {
                sh 'def click():/n print("click")'
            }
        }
        stage('Test') {
            steps {
                sh 'make test'
            }
        }
    }
}
