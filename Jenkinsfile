pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'GIT_COMMIT: ${GIT_COMMIT}'
        echo 'GIT_PREVIOUS_COMMIT: ${GIT_PREVIOUS_COMMIT}'
        echo 'Hello 0'
        echo 'Hello 1'
        echo 'Hello 2'
        echo 'Hello 5'
        echo 'Hello 6'
      }
    }
    stage('test') {
      steps {
          script {
             sleep (30)
          }
      }
    }
  }
}