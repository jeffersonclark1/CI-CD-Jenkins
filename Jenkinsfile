pipeline {
    agent none

    stages {
        stage ('Inicial') {
            steps {
                echo 'Initial pipeline'
            }
        }

        stage ('docker-compose') {
            agent any
            steps {
                sh 'docker-compose build'
            }
        }

        stage ('Finish deploy') {
            steps {
                echo 'Hello World'
            }
        }
    }
}