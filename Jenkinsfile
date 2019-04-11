pipeline {
  agent {
    docker {
      image 'maven:3-jdk-12-alpine'
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