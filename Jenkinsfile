pipeline {
    agent any

    stages {
        stage('CheckOut') {
            steps {
                echo 'CheckingOut'
            }
        }
        stage('Package') {
            steps {
                bat 'mvn clean package'
            }
        }
        stage('Publishing') {
            steps {
                echo 'Publishing'
            }
        stage('Publish') {
            steps {
                bat 'Publishing'
            }
        }
    }
}

