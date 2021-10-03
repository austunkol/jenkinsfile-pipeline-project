pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Congrast!!!'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
    }
}