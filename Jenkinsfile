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
        bat 'echo Test'
      }
    }
  }
  environment {
    Name = 'Rajesh'
  }
}
