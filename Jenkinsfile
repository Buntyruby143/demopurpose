pipeline {
  agent any
  stages {
    stage('Display Hello') {
      parallel {
        stage('Display Hello') {
          steps {
            echo 'Hi World, This is Naveen'
          }
        }

        stage('Sample step') {
          steps {
            sh '''echo "Below is the current date and time"
date'''
          }
        }

      }
    }

  }
}