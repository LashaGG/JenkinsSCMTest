pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            bat 'mvn clean test'
          }
        }

        stage('Maven Version') {
          steps {
            bat 'mvn --version'
          }
        }

      }
    }

  }
}