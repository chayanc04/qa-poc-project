pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/chayan/qa-poc-project.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
    }
}
