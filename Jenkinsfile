pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiling java source code'
                sh 'javac Hello.java'
            }
        }

        stage('run') {
            steps {
                echo 'Running teh compiled code'
                sh 'java Hello'
            }
        }

    }
}