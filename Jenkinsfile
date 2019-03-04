pipeline {
  agent none

  stages {
    stage('Build') {
      steps {
        echo 'GIT_COMMIT: ${env}'
        echo 'Hello 0d'
        echo 'Hello 1'
      }
    }
    stage('test') {
      steps {
        echo 'Hello 1'
      }
    }
  }
}