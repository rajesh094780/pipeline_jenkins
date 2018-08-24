pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            bat 'echo  %name%'
          }
        }
        stage('Build1') {
          steps {
            bat 'echo "Build"'
          }
        }
      }
    }
    stage('Test') {
      steps {
        bat 'echo "Test"'
      }
    }
  }
  environment {
    Name = 'Rajesh'
  }
}