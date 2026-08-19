pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'javac src\\Hello.java'
            }
        }

        stage('Test') {
            steps {
                bat 'java -cp src Hello'
            }
        }
    }
}