pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'python --version' // Checks Python version
      }
    }
    stage('hello') {
      steps {
        bat 'C:\Users\vaish\AppData\Local\Programs\Python\Python311\python.exe p1.py' 
      }
    }
  }
}
