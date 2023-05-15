pipeline {
    agent any

    stages {
        stage ('Inicial') {
            steps {
                echo 'Initial pipeline'
            }
        }

        stage ('Build') {
            steps {
                sh 'docker-compose build'
            }
        }

        stage ('Starning server') {
            steps {
                sh 'docker-compose up -d'
            }
        }

        stage ('Finish deploy') {
            steps {
                echo 'Hello World'
            }
        }
    }
}