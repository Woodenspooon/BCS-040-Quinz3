pipeline {
    agent any
    stages {
        stage('Build Java') {
            steps {
                sh 'javac HelloWorld.java'
                sh 'java HelloWorld'
            }
        }
    }
}
