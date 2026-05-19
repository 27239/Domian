pipeline {
    agent any

    environment {
        APP_NAME = "Domian"
    }

    stages {

        stage('Checkout') {
            steps {
                git branch: 'master',
                    url: 'https://github.com/27239/Domian.git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo Building project'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo Deploying application'
            }
        }
    }
}
