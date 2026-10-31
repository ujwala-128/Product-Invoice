
pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'source code Checked out completed'
            }
        }

        stage('Build') {
            steps {
                bat 'mvn clean compile'
            }
        }

        stage('Test') {
            steps {
                bat 'mvn test'
            }
        }

        stage('Package') {
            steps {
               bat 'mvn package'
            }
        }
    }
}


