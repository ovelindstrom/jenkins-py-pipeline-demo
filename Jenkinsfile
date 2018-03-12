pipeline {
    agent {
        docker { image 'python:2-alpine3.7' }
    }
    stages {
        stage('Version') {
            steps {
                sh 'python --version'
            }
        }
        stage('Build') {
            steps {
                sh 'python hello.py'
            }
        }
    }
}

