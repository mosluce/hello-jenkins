pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''echo $PATH
echo "==========="
ls -al /usr/bin/docker
echo "==========="
docker --version'''
      }
    }
  }
}