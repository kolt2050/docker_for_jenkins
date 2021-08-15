node {
    checkout scm
    cleanWs()
    docker.withRegistry('https://hub.docker.com') {

        docker.image('kolt2050/jenkins_docker_root').inside {
           sh 'docker --version'
           sh 'echo 1234'
           sh 'id'
           sh 'systemctl status docker'
           sh 'docker ps -a && docker images'
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
