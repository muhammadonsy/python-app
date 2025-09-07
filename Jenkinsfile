pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'docker build -t python-app .'
            }
        }
        stage('Run') {
            steps {
                sh 'docker-compose up -d'
            }
        }
    }
}

