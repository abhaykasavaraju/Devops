pipeline {
    agent any

    stages {
        stage('version') {
            steps {
                // Checkout the code from the GitHub repository
                bat'python3 --version'
            }
        }

        stage('Run Code3.py') {
            steps {
                // Run the Python script
                bat'python3 home.py'
            }
        }
    }
}
