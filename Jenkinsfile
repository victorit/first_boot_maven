pipeline {
  agent any
  stages {
    stage('prepare') {
      steps {
        sh 'env'
      }
    }

    stage('upload') {
      steps {
        archiveArtifacts '*.txt'
      }
    }

  }
}