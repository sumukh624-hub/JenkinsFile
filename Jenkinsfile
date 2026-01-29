pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Java application'
                bat 'mvn clean compile'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests'
                bat 'mvn test'
            }
        }
    }
}
