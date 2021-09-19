pipeline {
    agent {
        docker{
            image 'node:14.17.4-alpine3.13'
            args '-p 3000:3000'
        }
    }
    stages {
        stage('Build'){
            steps {
                sh 'npm install'
            }
        }
    }
}