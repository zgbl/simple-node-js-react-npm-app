pipeline {
    agent any
    tools {
        nodejs "NodeJS 22.8.0"
    }
    stages {
        stage('Verify Tools') {
            steps {
                sh 'node --version'
                sh 'npm --version'
            }
        }
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}