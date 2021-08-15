node {
    checkout scm
    cleanWs()
    docker.withRegistry('https://hub.docker.com') {

        docker.image('kolt2050/jenkins_docker_root').inside {
           sh 'docker --version'
           sh 'echo 1234'
        }
    }
    
    stage('Clone repo') {
        sh """#!/bin/bash
           echo "---------------ID--------------"
           id

        """

    }
}
