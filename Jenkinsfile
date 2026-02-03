pipeline {
  agent any
  stages {
    stage('build the code') {
      steps {
        sh 'mvn install'
      }
    }

  }
  environment {
    dev = ''
  }
}