pipeline {
    agent { docker 'node:6.3' }
    stages {
        stage('prepare') {
            steps {
                sh ". /etc/profile"
            }
        }
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}