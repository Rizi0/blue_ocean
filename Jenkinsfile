pipeline {
  agent {
    node {
      label 'docker'
    }

  }
  stages {
    stage('Testing') {
      parallel {
        stage('Testing') {
          steps {
            echo 'Testing'
          }
        }

        stage('Parallel') {
          steps {
            echo 'Parallel'
          }
        }

      }
    }

    stage('Build') {
      steps {
        echo 'Build'
      }
    }

    stage('Clean Up') {
      steps {
        echo 'Cleaning'
      }
    }

  }
}