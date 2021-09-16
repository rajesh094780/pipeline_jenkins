pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh "pwd"
          }
        }
        stage('Build1') {
          steps {
            sh "pwd"
          }
        }
      }
    }
    stage('Test') {
      steps {
        sh "pwd"
      }
    }
  }
  environment {
    Name = 'Rajesh'
  }
}
