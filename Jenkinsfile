pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''!example
'''
      }
    }
    stage('Test') {
      steps {
        sh 'newman run https://www.getpostman.com/collections/1fd9580419262ae1f409'
      }
    }
  }
}