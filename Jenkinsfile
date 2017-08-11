pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo hello'
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo Deploy'
      }
    }
    stage('Trigger UI') {
      steps {
        build 'Build_nodejs'
      }
    }
  }
}