pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Done'
      }
    }

    stage('test') {
      steps {
        echo 'test'
      }
    }

    stage('deploy') {
      steps {
        input(message: 'ask for Permition ', ok: 'Yes approved')
        echo 'Deployed'
      }
    }

    stage('NOtify') {
      steps {
        echo 'NOtifed '
      }
    }

  }
}