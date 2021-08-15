node {
    checkout scm
    cleanWs()
    docker.withRegistry('https://hub.docker.com') {

        docker.image('kolt2050/myhello').inside {
           sh 'docker --version'
           sh 'echo 1234'
        }
    }
    
    stage('Clone repo') {
        sh """#!/bin/bash
           docker ps -a && docker images
           echo "---------------ID--------------"
           id

        """

    }
}
