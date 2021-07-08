pipeline {
  agent any
  stages {
    stage('checkout and build') {
      steps {
        build 'mydemo2'
      }
    }

    stage('print') {
      steps {
        echo 'done'
      }
    }

  }
}