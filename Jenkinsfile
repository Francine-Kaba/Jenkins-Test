pipeline {
    agent any
    tools { nodejs 'node20' }
    
    stages {
        stage('build') {
            steps {
                sh 'node --version'
                sh "npm install"
            }
        }
    }
}