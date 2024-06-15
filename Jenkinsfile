pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build completed'
        timeout(time: 5, unit: 'SECONDS') {
       bat 'timeout /t 10 /nobreak'
        }
      }
    }
    stage('Test') {
      steps {
        echo 'Testing completed'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploy completed'
      }
    }
  }
}