pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'docker build -t adminturneddevops/go-webapp-sample .'
      }
    }
    stage('deploy') {
      steps {
        sh 'docker run -p 8090:8000 -d adminturneddevops/go-webapp-sample'
      }
    }
  }
}
