pipeline {
    agent none
 
    stages {
        stage('Docker test') {
            agent {
                dockerfile {
                filename "Dockerfile"
                }
            }
            steps {
                // Steps run in node:7-alpine docker container on docker slave
                sh 'node --version'
            }
        }

    }
}