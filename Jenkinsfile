pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build completed'
        timeout(time: 5, unit: 'SECONDS') {
        powershell 'Start-Sleep -Seconds 10'
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