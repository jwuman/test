pipeline {
  agent {
    docker {
      image 'jwuman/simple-web'
    }
    
  }
  stages {
    stage('Initialization') {
      steps {
        sh 'echo "Hello"'
      }
    }
    stage('Build') {
      steps {
        sh 'echo \'I am building\''
      }
    }
    stage('Test') {
      steps {
        sh 'echo \'I am testing\''
      }
    }
    stage('Deployment') {
      steps {
        sh 'echo \'I am deploying\''
      }
    }
  }
}
