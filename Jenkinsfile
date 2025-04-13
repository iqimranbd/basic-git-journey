pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/iqimranbd/basic-git-journey.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
                // Example build step
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Example test step
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Your deployment script here
            }
        }
        
         stage('Show File') {
            steps {
                // Display the file contents
                sh 'cat hello.txt'
            }
        }
    }
}
