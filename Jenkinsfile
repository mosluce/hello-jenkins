pipeline {
  agent {
    docker {
      image 'node:7.6.0'
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