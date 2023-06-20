pipeline {
  agent any
  stages {
    stage('Functional Test') {
      parallel {
        stage('Functional Test') {
          steps {
            bat 'mvn clean test'
          }
        }

        stage('Sleep') {
          steps {
            sleep(time: 500, unit: 'MILLISECONDS')
          }
        }

      }
    }

  }
}