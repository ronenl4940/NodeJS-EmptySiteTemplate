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








        
sleep 5 &&
curl localhost:8080
 && 






































        if     [["x$?" == "x0"]];
then    echo good;
else exit 1;
fi'''
      }
    }

  }
}