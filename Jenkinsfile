pipeline {
  agent any

  stages {        
    stage('Test') {
      steps {
        docker pull postman/newman_alpine33
        sh 'neman --version'
      }
    }               
  }
}

