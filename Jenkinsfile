pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Buil Completed...'
        timeout(time: 5, unit: 'SECONDS') {
          sh 'sleep 10'
        }
      }
    }
    stage('Test') {
      steps {
        echo 'Testing Completed...'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deployment Completed...'
      }
    }
  }
}