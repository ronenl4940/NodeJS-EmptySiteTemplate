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

  }
}