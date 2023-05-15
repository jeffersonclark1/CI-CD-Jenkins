pipeline {
    agent none

    stages {
        stage ('Inicial') {
            steps {
                echo 'Initial pipeline'
            }
        }

        stage('Back-end') {
            agent {
                docker { image 'docker-jefao_app' }
            }
            steps {
                sh 'docker ps'
            }
        }

        stage ('Finish deploy') {
            steps {
                echo 'Hello World'
            }
        }
    }
}