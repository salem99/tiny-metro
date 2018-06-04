pipeline {
  agent none
  stages {
    stage('Build_BO') {
      steps {
        echo 'aaaaa'
        build(job: 'tiny-metro-test/tiny-metro-test', propagate: true, wait: true)
      }
    }
  }
}