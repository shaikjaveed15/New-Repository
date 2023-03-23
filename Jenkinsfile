pipeline {
  agent any
  stages {
    stage('Devlopment') {
      steps {
        echo 'I want to Develop'
      }
    }

    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'I want to build'
          }
        }

        stage('Test') {
          steps {
            echo 'I want to test'
          }
        }

        stage('Deploy') {
          steps {
            echo 'I want to deploy'
          }
        }

      }
    }

  }
}