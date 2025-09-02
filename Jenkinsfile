pipeline {
  agent any
  stages {
    stage('python') {
      steps {
        // verifica Python
        bat 'python --version'
        // ejecuta tu script
        bat 'python back.py'
      }
    }
  }
}
