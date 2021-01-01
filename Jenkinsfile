pipeline {
  agent any
  stages {
    stage('demo') {
      parallel {
        stage('demo') {
          steps {
            echo 'ok'
          }
        }

        stage('') {
          steps {
            sh 'ls -l'
          }
        }

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

    stage('error') {
      steps {
        sh '''pwd
ls
ls -la'''
      }
    }

  }
}