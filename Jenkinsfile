pipeline {
    agent none
 
    stages {
        stage('Docker node test') {
            agent {
                dockerfile {
                filename "back-end/dockerfiles/ci/Dockerfile"
                }
            }
            steps {
                // Steps run in node:7-alpine docker container on docker slave
                sh 'node --version'
            }
        }

    }
}