pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo build'
      }
    }
    stage('Test') {
      steps {
        sh 'echo check'
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo Deploy'
        archiveArtifacts(excludes: '12', artifacts: '1233')
      }
    }
  }
}