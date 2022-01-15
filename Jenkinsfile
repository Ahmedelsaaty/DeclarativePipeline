pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build is completed'
      }
    }

    stage('Test1') {
      parallel {
        stage('Test1') {
          steps {
            echo 'complete 1'
          }
        }

        stage('Test2') {
          steps {
            echo 'Complete2'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'complete deployment'
      }
    }

  }
}