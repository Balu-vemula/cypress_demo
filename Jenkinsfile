pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'npm intall'
                sh 'npm install cypress@9.5.3'
                sh 'npx cypress open'
            }
        }
    }
}
