pipeline {
  agent any
  stages {
    stage('A') {
      steps {
        timeout(time: 10, unit: 'MINUTES') {
          timeout(time: 10, unit: 'MINUTES', activity: true)
        }

      }
    }

    stage('B') {
      steps {
        sh 'echo "Started stage B"'
      }
    }

  }
}