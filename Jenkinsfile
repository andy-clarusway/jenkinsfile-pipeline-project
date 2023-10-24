pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                whoami
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}
