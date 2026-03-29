pipeline {
  agent any
  stages {
    stage('full-path') {
      steps {
        sh 'cat my-dir/output.txt'
      }
    }

    stage('dir') {
      steps {
        dir('my-dir') {
          sh 'cat output.txt'
        }  
      }
    }
  }
}
