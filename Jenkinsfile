pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python3.10 --version'
      }
    }
    stage('hello') {
      steps {
        sh 'python3.10 hello.py'
      }
    }
  }
}
