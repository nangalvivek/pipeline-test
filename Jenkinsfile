pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        sh 'pwd'
        sh 'pwd'
        sh 'yarn install'
        sh 'ls -l node_modules'
      }
    }

    stage('build') {
      steps {
        sh 'pwd'
        sh 'yarn build'
        sh 'pwd'
        sh 'ls -l build'
      }
    }

    stage('test') {
      steps {
        sh 'pwd'
        sh 'pwd'
        sh 'pwd'
        sh 'pwd'
        sh 'pwd'
        sh 'pwd'
      }
    }

  }
}
