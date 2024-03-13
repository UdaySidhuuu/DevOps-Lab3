pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        echo 'Hello from ci pipeline'
      }
    }

    stage('Second Stage') {
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