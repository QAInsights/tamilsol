pipeline {
  agent any
  stages {
    stage('Parallel Build') {
      parallel {
        stage('Parallel Build') {
          steps {
            echo 'testing'
            echo 'Test'
          }
        }

        stage('One') {
          steps {
            echo 'test'
          }
        }

        stage('2') {
          steps {
            echo '3'
          }
        }

      }
    }

    stage('Test') {
      steps {
        echo 'test'
      }
    }

  }
}