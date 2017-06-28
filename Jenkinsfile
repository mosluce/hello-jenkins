pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''echo $PATH
echo "==========="
ls -al /usr/local/bin/docker
echo "==========="
docker --version'''
      }
    }
  }
}