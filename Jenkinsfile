pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/spring-projects/spring-petclinic'
            }
        }
         stage('Build') {
    steps {
        sh 'npm install'
    }
}
stage('Test') {
    steps {
        sh 'npm test'
    }
}
    }
}
