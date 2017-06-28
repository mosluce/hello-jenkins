pipeline {
  agent {
    docker {
      image 'node:8.1.2-alpine'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh '''echo "Hello, world"
echo $PATH
docker --version'''
      }
    }
  }
}