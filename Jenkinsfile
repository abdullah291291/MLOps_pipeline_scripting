pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Check out your source code repository here
                checkout scm
            }
        }

        stage('Build') {
            steps {
                // Define your build steps here
                bat 'C:\ProgramData\Anaconda3\python.exe sample.py'
                
            }
        }
    }
}
