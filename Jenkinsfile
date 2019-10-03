pipeline {
 agent {
   docker { image ‘postman/newman_alpine33’ }
 tools {nodejs “node js”}
 stages {
   stage(‘Install dependencies’) {
     steps {
       sh ‘npm install’
       sh ‘npm run api-test’
     }
   }
 }
}

