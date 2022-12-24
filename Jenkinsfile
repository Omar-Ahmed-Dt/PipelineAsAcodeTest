pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Buil Completed...'
 //       timeout(time: 5, unit: 'SECONDS') {
 //         sh 'sleep 2'
 //       }
      }
    }
    stage('Test') {
      parallel {
        stage('Test1') {
          steps {
            echo 'First test completed'
          }
        }

        stage('Test2') {
          steps {
            echo 'Second test completed'
          }
        }

      }
    }
    stage('Deploy') {
      steps {
        echo 'Deployment Completed...'
      }
    }
  }
}