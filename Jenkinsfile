pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'echo python is version is:'
                sh 'python --version'
            }
        }
    }
}


