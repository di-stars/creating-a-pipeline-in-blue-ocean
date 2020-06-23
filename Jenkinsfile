pipeline {
  agent any
  stages {
    stage('stage') {
      steps {
        retry(count: 4) {
          sleep 1
        }

      }
    }

  }
}