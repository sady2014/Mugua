pipeline {
  agent any
  stages {
    stage('Copy') {
      steps {
        bat(script: 'ping baidu.com -t', returnStatus: true, returnStdout: true)
      }
    }

  }
}