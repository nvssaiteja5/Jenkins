pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        sh 'docker build -t a /a/Dockerfile'
      }
    }
    stage('Deploy') {
      steps {
          sh 'docker run -d -p 1080:80 '
        }
      }
    }
  }
