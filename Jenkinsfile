pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python --version'
      }
    }
    stage('time') {
      steps {
        sh 'python current.py'
      }
    }
  }
}