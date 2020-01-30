pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build(quietPeriod: 5, wait: true, propagate: true, job: 'gradle build')
      }
    }

  }
}