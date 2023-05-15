pipeline {
    agent any

    stages {
        stage ('Inicial') {
            steps {
                echo 'Initial pipeline'
            }
        }

        stages {
            stage('docker-compose') {
                steps {
                    sh "docker-compose build"
                    sh "docker-compose up -d"
                }
            }
        }

        stage ('Finish deploy') {
            steps {
                echo 'Hello World'
            }
        }
    }
}