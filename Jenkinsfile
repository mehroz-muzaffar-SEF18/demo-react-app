pipeline {
    agent any
    tools {nodejs "Nodejs"}
    stages {
        stage('build') {
            steps {
                bat 'npm install'
            }
        }
        stage('deploy') {
            steps {
                bat 'npm str'
            }
        }
    }
}