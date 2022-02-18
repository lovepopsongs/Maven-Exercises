pipeline {
  agent any
  stages {
    stage('Hello world') {
      steps {
        echo 'HELLO WORLD!'
      }
    }

    stage('Compile') {
      steps {
        sh 'mvn clean install'
      }
    }

    stage('Ended') {
      steps {
        echo 'He acabado'
      }
    }

  }
}