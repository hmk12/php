pipeline {
  agent {
    docker {
      image 'php'
    }
    
  }
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
    stage('deployed') {
      steps {
        echo 'application deployed'
      }
    }
  }
  environment {
    Building = 'sh \'php --version\''
  }
}