pipeline {
  agent any
  stages {
    stage('P4 Sync') {
      steps {
        echo 'test'
      }
    }
    stage('Cook Game') {
      parallel {
        stage('Make Main Build') {
          steps {
            build(job: 'test', wait: true)
            archiveArtifacts '/game'
          }
        }
        stage('Make Test Build') {
          steps {
            echo 'test'
          }
        }
      }
    }
    stage('Run Tests') {
      steps {
        echo 'test'
      }
    }
    stage('Send Reports') {
      steps {
        echo 'test'
      }
    }
  }
}