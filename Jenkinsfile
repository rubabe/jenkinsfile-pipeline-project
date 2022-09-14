pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'This message come from Jenkins Groovy Language'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
    }
}
