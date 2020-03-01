node {
    def app

    stage('Clone repository') {
        /* Let's make sure we have the repository cloned to our workspace */

        checkout scm
    }
    stage('Test') {
        
        echo 'Testing..'

        app = docker.build("kvoth/jenkins-docker-node-test")        
     }
    stage('Deploy') {
        
        echo 'Deploying....'
    }    
}