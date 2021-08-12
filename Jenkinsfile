pipeline {
  agent any
  stages {
    stage('checkout code') {
      steps {
        git 'https://github.com/ronenl4940/NodeJS-EmptySiteTemplate.git'
      }
    }

    stage('build & compile') {
      steps {
        sh 'npm install'
      }
    }

    stage('test code') {
      steps {
        sh '''node server.js &


curl localhost:8080
sleep 5 &&




if [[ "x$?" == "x0" ]]; then    echo good; else exit 1; fi




'''
      }
    }

  }
}