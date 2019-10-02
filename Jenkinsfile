pipeline {
  agent {
    docker { image 'postman/newman_alpine33' }

  stages {        
    stage('Test') {
      steps {
        sh 'neman --version'
      }
    }               
  }
}

