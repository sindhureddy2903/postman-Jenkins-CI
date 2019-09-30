pipeline {
  agent any

  tools {nodejs "node js"}

  stages {        
    stage('Install dependencies') {
      steps {
        sh 'npm install'
        sh 'npm run api-test'
      }
    }               
  }
}

