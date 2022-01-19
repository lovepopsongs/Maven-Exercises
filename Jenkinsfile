pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mvn -X clean install -Dlicense.skip=true'
      }
    }

  }
}