pipeline {
  agent {
    docker {
      image 'alpine'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'echo "Halllo, world"'
      }
    }
  }
}