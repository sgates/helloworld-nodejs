pipeline {
  agent {
    node {
      label 'nodeAgent'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'Hello World!'
        sh 'java -version'
      }
    }
  }
}