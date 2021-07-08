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

    stage('script') {
      steps {
        bat(script: 'C:/tmp1/notepad1.bat', returnStdout: true)
      }
    }

  }
}