pipeline {
  agent none
  stages {
    stage('Build_BO') {
      steps {
        sh 'ls'
        echo 'aaaaa'
        timeout(time: 10)
        bat(script: 'aadf', encoding: 'asdf', returnStatus: true, returnStdout: true)
      }
    }
  }
}