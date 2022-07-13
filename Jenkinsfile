pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'npm install'
                sh 'npm install cypress@9.5.3'
                sh 'npm run'
            }
        }
    }
}
