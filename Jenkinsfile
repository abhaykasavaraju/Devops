pipeline {
    agent any

    stages {
        stage('version') {
            steps {
                // Checkout the code from the GitHub repository
                bat'py --version'
            }
        }

        stage('Run Code3.py') {
            steps {
		dir('directory1') {
			// Run the Python script
                	bat'py code3.py'
		}
                
            }
        }
    }
}
