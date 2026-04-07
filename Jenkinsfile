pipeline {
    agent any

    stages {

        stage('Git Check') {
            steps {
                echo 'Git에서 Jenkinsfile 실행 성공'
            }
        }

        stage('Check Files') {
            steps {
                sh 'pwd'
                sh 'ls -al'
            }
        }

    }
}