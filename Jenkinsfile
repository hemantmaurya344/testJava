pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        sh 'echo passed'
      }
    }
    stage('Build and Test') {
      steps {
        sh 'mvn clean package'
      }
    }
  }
}
