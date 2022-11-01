pipeline {
    agent any
    tools {
        maven "main"
    }
    stages {
        stage('Checkout') {
            steps {
                // Get some code from a GitHub repository
                git url: 'https://github.com/Ziravine/jenkinclass.git', 
                    branch: 'main',
                    credentialsId: '404b6af5-bc30-4b8d-84f0-5912457ec47c'
            }
        }
    }
}