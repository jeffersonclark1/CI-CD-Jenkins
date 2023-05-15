pipeline {
    agent any

    stages {
        stage('Test') {
            agent any
            steps {
                sh label: '', script: '''
                    docker ps
                '''
            }
        }
    }
}