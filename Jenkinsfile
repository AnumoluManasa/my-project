pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/AnumoluManasa/my-project.git'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
    }
}
