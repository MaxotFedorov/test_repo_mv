pipeline {
    agent { label 'server' }

    stages {
        stage('echo') {
            steps {
                echo 'Hello World!'
            }
        }
        stage('pwd') {
            steps {
                sh 'pwd'
            }
        }
        stage('ls -a ') {
            steps {
                sh 'ls -a'
            }
        }
        stage('whoami') {
            steps {
                sh 'whoami'
            }
        }
    }
}