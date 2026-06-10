pipeline {
    agent any

    stages {
        stage('Inspect') {
            steps {
                sh 'pwd'
                sh 'ls'
            }
        }

        stage('Test') {
            steps {
                sh 'test -f Jenkinsfile'
                sh 'test -d lessons'
                sh 'test -d reference'
            }
        }
    }
}
