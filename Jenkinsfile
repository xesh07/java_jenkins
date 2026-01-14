pipeline {
    agent any

    stages {
        stage('Checkout Verification') {
            steps {
                echo 'Repository checked out successfully'
                sh 'ls -l'
            }
        }

        stage('Environment Check') {
            steps {
                sh 'java -version'
            }
        }
    }
}
