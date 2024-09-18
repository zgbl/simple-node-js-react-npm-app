pipeline {
    agent any
    tools {
        nodejs "NodeJS 22.8.0" // Use the name you gave in Global Tool Configuration
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}