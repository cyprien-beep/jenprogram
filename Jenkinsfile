pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                bat 'dir'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                bat 'echo Tests passed!'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                bat 'echo Deployment complete!'
            }
        }
    }
}
