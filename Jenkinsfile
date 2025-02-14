pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'echo Integrating Jenkins Pipeline with GitHub Webhook using Jenkinsfile'
            }
        }
        stage ('build-java') {
            steps {
                echo 'Compiling the java source code'
                sh 'javac Hello.java'
            }
        }
        stage ('run-java') {
            steps {
                echo 'Running the compiled java code.'
                sh 'java Hello'
            }
        }

    }
}
