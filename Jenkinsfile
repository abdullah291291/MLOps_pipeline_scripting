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
                script {
                    // git branch: 'main', url: 'https://github.com/abdullah291291/MLOps_pipeline_scripting'
                    sh 'python3 sample.py'
                }
            }
        }
    }
}
