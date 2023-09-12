pipeline {
    agent any

    stages {
        stage('SCM checkout') {
            steps {
                echo 'Checkout code from GitHub'
            }
        }
        stage('Maven Build') {
            steps {
                echo 'Compile and Package the source code'
            }
        }
        stage('Code Quality Check') {
            steps {
                echo 'Check the codes for vulnerability and Bugs'
            }
        }
        stage('Testing') {
            steps {
                echo 'Test the application using tools like Selenium'
            }
        }
        stage('Docker Image Build') {
            steps {
                echo 'Build Docker Image'
            }
        }
        stage('Deploy Docker Container') {
            steps {
                echo 'Deploy the Application in Containers'
            }
        }
    }
}
