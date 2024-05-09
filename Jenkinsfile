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
                // Run the Python script
                sh 'python Devops/directory1/code3.py'
            }
        }
    }
}
