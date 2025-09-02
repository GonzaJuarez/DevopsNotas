pipeline {
  agent any
  stages {
    stage('diag'){
      steps{
        bat 'where python || echo no-python'
        bat 'where py || echo no-py'
        bat 'echo %PATH%'
      }
    }
    stage('python') {
      steps {
        bat '"C:\\Users\\Usuario\\AppData\\Local\\Programs\\Python\\Python312\\python.exe" --version'
        bat '"C:\\Users\\Usuario\\AppData\\Local\\Programs\\Python\\Python312\\python.exe" back.py'
      }
    }
  }
}
