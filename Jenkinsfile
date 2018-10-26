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
        sh 'npm install'
      }
    }
    stage('test') {
      steps {
        echo 'testing is done'
      }
    }
  }
}