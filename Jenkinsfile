pipeline {
    agent {
        docker {
            image 'node:10.18.1-alpine3.10' 
            args '-p 3000:3000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'yarn install' 
                sh 'yarn start'
            }
        }
    }
}