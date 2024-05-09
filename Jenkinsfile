pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from the GitHub repository
                git 'https://github.com/abhaykasavaraju/Devops.git'
            }
        }

        stage('Run Code3.py') {
            steps {
                dir('directory1') {
                    // Run the Python script
                    sh 'python code3.py'
                }
            }
        }
    }
}
