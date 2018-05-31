pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        build(propagate: true, job: 'maven')
      }
    }
  }
}