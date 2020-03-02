pipeline {
    agent { dockerfile true }
 
    stage('Clone repository') {
        /* Let's make sure we have the repository cloned to our workspace */

        checkout scm
    }
   stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}