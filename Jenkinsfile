pipeline {
  agent {
    docker {
      image 'node:8.1.2-alpine'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh 'npm --version'
      }
    }
  }
  environment {
    PATH = '$PATH:/usr/local/bin'
  }
}