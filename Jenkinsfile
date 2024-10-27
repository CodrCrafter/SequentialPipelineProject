pipeline {
    agent any 
    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out the code...'
                git 'https://github.com/CodrCrafter/SequentialPipelineProject.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Add build steps here
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add test steps here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Add deployment steps here
            }
        }
    }
    post {
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed.'
        }
    }
}
