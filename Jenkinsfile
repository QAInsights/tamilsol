pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'testing'
          }
        }

        stage('One') {
          steps {
            echo 'Test'
          }
        }

      }
    }

  }
}