pipeline {
  agent any
  stages {
    stage('deployment') {
      steps {
        sh ' sh \'deploymnet in process\''
      }
    }
    stage('testing') {
      steps {
        sh 'sh \'application in testing mode\''
      }
    }
    stage('production') {
      steps {
        sh 'sh \'application in production mode\''
      }
    }
  }
  environment {
    Building = 'sh \'php --version\''
  }
}