pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'to Reinvent Yourself'
                sh 'python --version'
                sh 'git --version'
                sh 'python pipeline.py'
            }
        }
    }
}