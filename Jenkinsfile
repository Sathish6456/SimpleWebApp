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
        stage('JaCoCo Report') {
            steps {
                jacoco()
            }
        }
    }
}

