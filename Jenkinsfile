pipeline {
  agent any
  stages {
    stage('Functional Test') {
      steps {
        bat 'mvn clean test'
      }
    }

    stage('Sleep') {
      steps {
        sleep 10
      }
    }

  }
}