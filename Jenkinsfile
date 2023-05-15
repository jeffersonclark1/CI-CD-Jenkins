pipeline {
    agent any

    stages {
        stage ('Inicial') {
            steps {
                echo 'Initial pipeline'
            }
        }

        stage ('Update project') {
            sh 'docker-compose restart docker-jefao_app_1'
        }
    }
}