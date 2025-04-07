pipeline {
    agent {
        docker {
            image 'node:18' // atau versi Node.js yang kamu butuhkan
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                sh 'npm test'
            }
        }
    }
}
