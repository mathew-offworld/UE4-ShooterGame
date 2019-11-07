pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Win64 Client') {
          steps {
            echo 'test'
          }
        }
        stage('Win64 Server') {
          steps {
            echo 'test'
          }
        }
        stage('Linux Server') {
          steps {
            echo 'test'
          }
        }
        stage('Editor') {
          steps {
            echo 'test'
          }
        }
      }
    }
    stage('Smoke Test') {
      parallel {
        stage('Functional Test') {
          steps {
            echo 'test'
          }
        }
        stage('UI Test') {
          steps {
            echo 'test'
          }
        }
        stage('Editor Test') {
          steps {
            echo 'test'
          }
        }
      }
    }
    stage('Deploy to Steam') {
      parallel {
        stage('Win64 Client') {
          steps {
            echo 'test'
          }
        }
        stage('Win64 Server') {
          steps {
            echo 'test'
          }
        }
      }
    }
    stage('Report') {
      steps {
        echo 'test'
      }
    }
  }
}