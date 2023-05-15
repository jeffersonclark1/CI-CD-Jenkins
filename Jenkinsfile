pipeline {
    agent any

    stages {
        stage ('Inicial') {
            steps {
                echo 'Initial pipeline'
            }
        }

        stage('docker-compose') {
            steps {
                sh './wait-for.sh'
            }
        }

        stage ('Finish deploy') {
            steps {
                echo 'Hello World'
            }
        }
    }
}