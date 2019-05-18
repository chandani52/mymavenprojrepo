pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build(job: 'mymavenprojrepo', quietPeriod: 5, wait: true)
      }
    }
  }
  environment {
    satge = 'build'
    stage = 'sit'
  }
}