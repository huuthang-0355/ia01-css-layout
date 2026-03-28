pipeline {
  agent any
  stages {
    stage('Building...') {
      steps {
        nodejs('Node') {
          echo 'Building application...'
          sh 'npm install'
        }
      }
    }
  }
}
