pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/tspatel02/mysimplepipeline.git'
            }
        }

        stage('Build') {
            steps {
                bat 'echo Building application'
            }
        }

        stage('Test') {
            steps {
                bat 'echo Running tests'
            }
        }

        stage('Deploy') {
            steps {
                bat 'echo Deploying'
            }
        }

    }
}
