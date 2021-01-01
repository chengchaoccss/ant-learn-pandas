pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        bat(script: 'echo "build"', returnStatus: true, returnStdout: true)
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