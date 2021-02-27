pipeline {
  agent any
  stages {
    stage('stas') {
      parallel {
        stage('stas') {
          steps {
            stash(name: 'test', useDefaultExcludes: true)
          }
        }

        stage('') {
          steps {
            echo 'test'
          }
        }

      }
    }

    stage('unstash') {
      steps {
        unstash 'stas'
      }
    }

  }
}