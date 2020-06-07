pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'This is buiding statge'
      }
    }

    stage('Test') {
      steps {
        echo 'This is testing statge'
      }
    }

    stage('Approval') {
      steps {
        input 'Do you want to deploy app?'
      }
    }

    stage('Deploy') {
      steps {
        echo 'This is deploy statge'
      }
    }

  }
}