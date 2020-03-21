pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo Building ${BRANCH_NAME}...'
      }
    }
    stage('test') {
      steps {
        sh 'echo This is Testing stage'
      }
    }
    stage('deploy') {
      steps {
        sh 'echo this is deployment stage'
      }
    }
  }

}
