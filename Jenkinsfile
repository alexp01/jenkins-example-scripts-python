pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python --version'
      }
    }
    stage('hello') {
      steps {
        sh 'python -u all_tests.py  --command check_artfiacts'
      }
    }
  }
}