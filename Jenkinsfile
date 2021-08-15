node {
    checkout scm
    //cleanWs()
    docker.withRegistry('https://hub.docker.com') {

        docker.image('docker pull bitnami/jenkins').inside {
           sh 'docker --version' 
           sh 'echo 1234'
        }
    }
    stage('Clone repo') {
        println("HELLO")
           sh """#!/bin/bash
           echo "---------------ID--------------"
      #     id
           #ls -la edp-install/
#
           #rm -rf * 
           #docker rmi -f \$(docker images -q) && docker rm -f \$(docker ps -aq)

#           git clone https://github.com/epam/edp-install.git
#           pwd && ls -la
#           cd edp-install
           
#           echo "---------we in edp-install----------"
           #docker images
           #docker ps -all
#           pwd 

#           sed -i 's/docker run --rm -it/docker run --rm -i/' Makefile 
#           cat Makefile
#           make build-docs 

#           echo "---------------site is here--------------" 
#           ls -la ../ 
#           mv site ../
           #git checkout gh-pages
#           ls -la
           #rm -rf *
           #echo "Clear gh-pages"
           #cp ../site .
           #ls -la
           """
        
    }
}
