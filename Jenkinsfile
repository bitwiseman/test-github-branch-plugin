pipeline {
  agent none
  stages {
    stage('Build') {
      steps {
        echo 'GIT_COMMIT: ${GIT_COMMIT}'
        echo 'GIT_PREVIOUS_COMMIT: ${GIT_PREVIOUS_COMMIT}'
        echo 'Hello 0d'
        echo 'Hello 2'
        echo 'Hello 3'
        echo 'Hello 5'
        echo 'Hello 6'
        echo 'Hello 7'
      }
    }
    stage('test') {
      steps {
          script {
            a = readTrusted ('Jenkinsfile')
            echo  a
            sleep (30)
          }
      }
    }
  }
}