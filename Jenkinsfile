pipeline {
    agent any

    stages {
        stage('version') {
            steps {
                // Checkout the code from the GitHub repository
                sh 'python --version'
            }
        }

        stage('Run Code3.py') {
            steps {
                // Run the Python script
                sh 'python /directory1/code3.py'
            }
        }
    }
}
