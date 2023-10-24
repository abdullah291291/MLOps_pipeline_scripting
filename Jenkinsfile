pipeline {
    agent any

    stages {
        stage("Checkout") {
            steps {
                // Check out your source code repository here
                checkout scm
            }
        }

        stage("Build") {
            steps {
                // Define your build steps here
                bat 'echo %PATH%'
                // bat 'where python'
                bat '"C:\Users\abdul\AppData\Local\Programs\Python\Python311\python.exe" sample.py'
            }
        }
    }
}
