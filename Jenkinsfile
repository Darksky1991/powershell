pipeline {
  agent any
  stages {
    stage('1') {
      parallel {
        stage('1') {
          agent any
          steps {
            sh 'echo 1'
          }
        }

        stage('2') {
          agent any
          steps {
            sh 'echo 2'
          }
        }

      }
    }

    stage('3') {
      steps {
        sh 'echo 3'
      }
    }

  }
}