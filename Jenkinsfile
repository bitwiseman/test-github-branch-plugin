pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'GIT READY!'
        echo 'GIT READY!'
        echo 'GIT_COMMIT: ${GIT_COMMIT}'
        echo 'GIT_PREVIOUS_COMMIT: ${GIT_PREVIOUS_COMMIT}'
        echo 'Hello 0'
        echo 'Hello 1'
        echo 'Hello 2'
        echo 'Hello 3'
        echo 'Hello 5'
        echo 'Hello 6'
        echo 'Hello 7'
        echo 'Hello 8'
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
