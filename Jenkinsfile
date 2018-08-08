pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('CI') {
      steps {
        sh 'sh `pwd`'
      }
    }
  }
}