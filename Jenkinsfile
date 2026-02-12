pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                javac main.java
                java main.java
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
