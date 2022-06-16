pipeline {
  agent any
  stages {
    stage('blue') {
      parallel {
        stage('blue') {
          steps {
            sh 'echo "hi"'
          }
        }

        stage('ocean') {
          steps {
            echo 'Hello'
          }
        }

      }
    }

    stage('choose') {
      steps {
        sh 'echo "good"'
      }
    }

  }
}