pipeline {
    agent any
    tools {
        maven 'Maven 3.6.3'
    }
    stages {
        stage('build') {
            steps {
                echo 'hello world'
                sh 'java --version'
                sh 'mvn clean compile'
            }

        }
        stage('test') {
            steps {
                sh 'mvn test'
            }
        }
    }
}