pipeline {
    agent any
    tools { nodejs 'node22' }

    stages {
        stage('build') {
            steps {
                sh 'node --version'
                sh "npm install"
            }
        }
    }
}