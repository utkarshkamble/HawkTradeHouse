pipeline {
  agent {
    docker {
      image 'alpine'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'Build step is executed'
      }
    }
    stage('test') {
      steps {
        echo 'testing is done'
      }
    }
  }
}