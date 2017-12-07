pipeline {
  agent any
  stages {
    stage('ls') {
      parallel {
        stage('ls') {
          steps {
            echo 'test'
          }
        }
        stage('bash') {
          steps {
            sh 'ls -al'
          }
        }
      }
    }
  }
}