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
        sh 'echo "Hello, world"'
      }
    }
  }
}