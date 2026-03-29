pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'Testing...' 
      }
    }

    stage('build') {

      when {
        changeset '**/*.sh'
      }
      
      steps {
        echo 'Building...'
      }
    }

     stage('deploy') {
      steps {
        echo 'Deploying...'
      }
    }
  }
}
