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
                echo %PATH%
                // bat 'python sample.py'
            }
        }
    }
}
