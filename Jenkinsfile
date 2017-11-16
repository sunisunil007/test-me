pipeline {
  agent any
  stages {
    stage('parallel_test1') {
      parallel {
        stage('stage1') {
          steps {
            sh 'echo "test1"'
          }
        }
        stage('') {
          steps {
            echo 'stage2'
          }
        }
      }
    }
    stage('conclude') {
      steps {
        echo 'finished pipeline'
      }
    }
  }
}