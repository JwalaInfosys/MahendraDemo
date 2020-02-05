pipeline {
  agent any
  stages {
    stage('Preparation') {
      steps {
        echo 'I am new to Jenkins file'
      }
    }

    stage('Compile') {
      steps {
        sh 'echo hostname'
      }
    }

    stage('Deploye') {
      steps {
        retry(count: 1) {
          echo 'Test'
        }

      }
    }

  }
}