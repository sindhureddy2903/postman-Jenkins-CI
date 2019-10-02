pipeline {
  agent {
    docker { 
      label 'docker'
      image 'postman/newman_alpine33' 
      entrypoint '[""]'
    }
  }

  stages {        
    stage('Test') {
      steps {
        sh 'neman --version'
      }
    }               
  }
}

