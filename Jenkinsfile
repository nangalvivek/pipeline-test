pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        sh 'yarn install'
      }
    }

    stage('build') {
      steps {
        sh 'yarn build'
      }
    }

    stage('test') {
      steps {
        sh 'yarn test'
      }
    }

  }
}