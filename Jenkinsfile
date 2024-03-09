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
        echo 'test2'
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
