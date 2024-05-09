pipeline {
    agent any

    stages {
        stage('Run Code3.py') {
            steps {
                dir('directory1') {
                    sh 'python code3.py'
                }
            }
        }
        stage('Run Code.py in directory2') {
            steps {
                dir('directory2') {
                    sh 'python code.py'
                }
            }
        }
        stage('Run Code.py in directory3') {
            steps {
                dir('directory3') {
                    sh 'python code.py'
                }
            }
        }
    }
}
