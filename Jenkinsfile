pipeline {
    agent any
    tools {
        nodejs "NodeJS1"
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