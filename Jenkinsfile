pipeline {
  agent any
  stages {
    stage('Testing') {
      parallel {
        stage('Testing') {
          steps {
            echo 'Testing'
          }
        }

        stage('Parrellel') {
          steps {
            echo 'running in Parrellel'
          }
        }

      }
    }

    stage('Build') {
      steps {
        echo 'Building'
      }
    }

    stage('Clean up') {
      steps {
        echo 'Cleaning'
      }
    }

  }
}