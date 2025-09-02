pipeline {
  agent any
  stages {
    stage('python') {
      steps {
        bat 'py -3 --version'
        bat 'py -3 back.py'
      }
    }
  }
}
