pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'build completed'
        timeout(time: 5, unit: 'SECONDS') {
           sh 'sleep 10'
        }
      }
    }
    stage('test') {
      steps {
        echo 'test completed'
      }
    }
    stage('deploy') {
      steps {
        echo 'deploy completed'
      }
    }

  }
}