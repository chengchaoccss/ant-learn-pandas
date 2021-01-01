pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            bat(script: 'echo "build"', returnStatus: true, returnStdout: true)
          }
        }

        stage('demo') {
          steps {
            echo 'ok'
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

  }
}