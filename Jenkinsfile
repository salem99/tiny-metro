pipeline {
  agent none
  stages {
    stage('Build_BO') {
      steps {
        echo 'aaaaa'
        build(job: 'tiny-metro-test', propagate: true, wait: true, quietPeriod: 1)
      }
    }
  }
}