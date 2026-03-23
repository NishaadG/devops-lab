pipeline {
    agent any 

    stages {
        stage('Build') {
            steps {
                echo 'Building... (Compiling code)'
                // If Java: sh 'javac HelloWorld.java'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing... (Running unit tests)'
                // If Java: sh 'java HelloWorld'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying... (Application is live)'
            }
        }
    }
}
