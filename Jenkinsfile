pipeline {
    agent any
    stages {
        stage('Build Java') {
            steps {
                bat 'javac HelloWorld.java'
                bat 'java HelloWorld'
            }
        }
    }
}
