pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        echo 'hello from ci pipeline'
      }
    }

    stage('Second stage') {
      steps {
        sleep 100
      }
    }

    stage('Build') {
      steps {
        build 'job one'
      }
    }

  }
}