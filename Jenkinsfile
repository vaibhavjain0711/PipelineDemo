pipeline {
    agent any
    
    stages {
        stage('Checking Version') {
            steps {
                bat 'javac -version'
            }
        }
        stage('Compiling') {
            steps {
                bat 'javac hello.java'
            }
        }
        
        stage('Running') {
            steps {
                bat 'java Hello'
            }
        }
    }
}
