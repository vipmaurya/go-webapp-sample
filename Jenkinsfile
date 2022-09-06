pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        image = docker.build("adminturneddevops/go-webapp-sample")
        sh "docker run -p 8090:8000 -d adminturneddevops/go-webapp-sample"
      }
    }
  }
}
