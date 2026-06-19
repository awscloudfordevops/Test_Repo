pipeline {
    agent any

    stages {

        stage('Info') {
            steps {
                sh 'whoami'
                sh 'pwd'
            }
        }

        stage('Files') {
            steps {
                sh 'ls -la'
            }
        }

    }
}
