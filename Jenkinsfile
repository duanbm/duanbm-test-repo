pipeline {
    agent {
        node {
            label 'jenkins-docker-node-01'
            }
        }
    stages {
        stage('build') {
            steps {
                script {
                    sh "echo hello world"
                }
            }
        }
    }
}