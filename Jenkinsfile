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
        sh '''chmod 777 test.sh
./test.sh'''
      }
    }

    stage('package code') {
      steps {
        sh '''tar -czvf node.tar.gz .


  '''
      }
    }

  }
}