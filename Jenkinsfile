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
                bat '"C:\Users\abdul\AppData\Local\Microsoft\WindowsApps\python.exe" sample.py'
                
            }
        }
    }
}
