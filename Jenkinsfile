pipeline {
  agent any
  stages {
    stage('full-path') {
      steps {
        sh 'cat my-dir/output.txt'
      }
    }

    stage('dir') {
      dir('my-dir') {
        sh 'cat output.txt'
      }
    }
  }
}
