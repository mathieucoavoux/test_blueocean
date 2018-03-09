pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'echo hello'
      }
    }
    stage('stage2') {
      steps {
        input(message: 'hello input', id: 'name', ok: 'e', submitter: 'd', submitterParameter: 'f')
      }
    }
  }
}