/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'php:8.4.2-alpine3.21' } }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}
