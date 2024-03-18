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
    stage('Deploy'){
      sh 'java -jar /var/lib/jenkins/workspace/SampleJava/target/demo-0.0.1-SNAPSHOT.jar'
    }
  }
}
