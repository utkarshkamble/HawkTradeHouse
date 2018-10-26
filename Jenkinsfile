pipeline {
  agent {
    docker {
      args '-p 3030:3000'
      image 'alpine'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
  }
}
