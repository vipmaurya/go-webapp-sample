pipeline {
  agent any
  stages {
    stage('dev') {
      steps {
        sh 'docker build -t https://kodekloud.com/topic/lab-building-a-cd-pipeline/ ./...'
      }
    }

  }
}
