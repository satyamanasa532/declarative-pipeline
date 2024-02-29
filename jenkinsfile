pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Run your build commands here
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Run your tests here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Deploy your application here
            }
        }
    }
    post {
        success {
            echo 'Pipeline succeeded!'
            // Additional actions to take upon success
        }
        failure {
            echo 'Pipeline failed!'
            // Additional actions to take upon failure
        }
    }
}
