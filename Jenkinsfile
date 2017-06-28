pipeline {
  agent any
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