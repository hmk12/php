pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh ' echo \'Hello world!\''
      }
    }
    stage('Testing') {
      steps {
        sh 'echo \'testing in progress\''
      }
    }
    stage('Deployment') {
      steps {
        sh 'echo \'Deployment in progress\''
      }
    }
    stage('Production') {
      steps {
        sh 'echo \'application in production mode\''
      }
    }
  }
}