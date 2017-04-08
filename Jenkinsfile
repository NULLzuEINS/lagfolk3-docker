pipeline {
  agent {
    docker {
      image 'ubuntu'
      args 'latest'
    }
    
  }
  stages {
    stage('Echo') {
      steps {
        echo 'Build container'
        sh 'docker-compose build'
      }
    }
  }
}