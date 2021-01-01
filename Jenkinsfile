pipeline {
  agent any
  stages {
    stage('demo') {
      steps {
        echo 'ok'
      }
    }

    stage('test') {
      steps {
        echo 'blueocean'
      }
    }

    stage('end') {
      steps {
        echo 'end'
      }
    }

    stage('') {
      steps {
        sh '''pwd
ls
ls -la'''
      }
    }

  }
}