pipeline {
    agent any

    stages {
        stage('version') {
            steps {
                // Checkout the code from the GitHub repository
                bat'C:\Program Files\Python312\python.exe --version'
            }
        }

        stage('Run Code3.py') {
            steps {
                // Run the Python script
                bat'C:\Program Files\Python312 hoem.py'
            }
        }
    }
}
