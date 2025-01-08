@Library('shared-testlib') _

pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        welcome("Hello everyone")
        script{
          welcome.add(2,5)
          welcome.sub(2,9)
        }
      }
    }
  }
}
