pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo 'Hello World'
      }
    }

    stage('QA') {
      steps {
        input(message: 'Deploy?', ok: 'Yes')
      }
    }

  }
}