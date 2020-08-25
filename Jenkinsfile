pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            input(message: 'aru you ready', id: 'ready', ok: 'yes', submitter: 'admin', submitterParameter: 'yes')
          }
        }

        stage('shell') {
          steps {
            echo 'hello'
          }
        }

      }
    }

  }
}