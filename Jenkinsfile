/* pipeline {
    environment {
        registry = 'jenk_deneme/ml_model'
        dockerImage = ''
    }
    agent any
    stages {
        stage('Build Docker Image') {
            agent any
            steps {
                script {
                    dockerImage = docker.build registry + ":$BUILD_NUMBER"
                }
            }
        }

    }
} */

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}