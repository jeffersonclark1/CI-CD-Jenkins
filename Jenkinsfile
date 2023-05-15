pipeline {
    agent any

    stages {
        stage ('Inicial') {
            steps {
                echo 'Initial pipeline'
            }
        }

        stage ('Update project') {
            steps {
                sh 'docker-compose restart docker-jefao_app_1'
            }
        }
    }
}