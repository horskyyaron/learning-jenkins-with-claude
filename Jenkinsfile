pipeline {
    agent any

    stages {
        stage('Inspect') {
            steps {
                sh 'pwd'
                sh 'ls'
            }
        }

        stage('Build') {
            steps {
                sh 'mkdir -p build'
                sh 'printf "Jenkins learning workspace\n" > build/summary.txt'
                sh 'ls build'
            }
        }

        stage('Test') {
            steps {
                sh 'test -f Jenkinsfile'
                sh 'test -d lessons'
                sh 'test -d reference'
                sh 'test -f build/summary.txt'
            }
        }
    }
}
