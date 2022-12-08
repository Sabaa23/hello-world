pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/vsknalli/first-app.git', branch: 'main')
      }
    }

    stage('Test') {
      steps {
        echo 'Testjob'
      }
    }

    stage('bundle') {
      steps {
        echo 'Bundle it '
      }
    }

  }
}