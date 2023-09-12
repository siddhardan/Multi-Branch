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
    }
}
