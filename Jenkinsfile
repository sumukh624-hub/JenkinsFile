pipeline {
    agent any // Specifies where the pipeline will run, 'any' uses any available agent
    stages {
        stage('Build') {
            steps {
                echo 'Building...' // Echo is a built-in step
                // Add your build commands here, e.g., sh 'mvn clean install'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Add your test commands here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add your deployment commands here
            }
        }
    }
}
