pipeline {
    agent { label 'demo' }
    
    stages {
        stage('Check Version') {
            steps {
                script {
                    sh 'node --version'
                    sh 'npm --version'
                }
            }
        }
    }
}
