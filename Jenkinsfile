pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building application'
                mvn clean compile
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests'
                mvn test
            }
        }
    }
}
