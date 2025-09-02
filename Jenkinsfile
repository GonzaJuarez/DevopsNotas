pipeline {
  agent any
  stages {
    stage('python') {
      steps {
        bat 'where python || echo no-python'
        bat 'where py || echo no-py'
        bat 'echo %PATH%'
        bat 'py -3 --version'
        bat 'py -3 back.py'
      }
    }
  }
}
