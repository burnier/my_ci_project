pipeline {
    agent { docker { image 'python:3.7.2' } }
    stages {
        stage('build') {
            steps {
                sh 'pip install flask
            }
        }
        stage('test_hello') {
            steps {
                sh 'python -m unittest test_hello.py'
            }
        }
    }
}