node {
   stage('Postman Jenkins CI'){
      git 'https://github.com/sindhureddy2903/postman-Jenkins-CI.git'
   }
   stage('Install Node Dependencies'){
      bat 'npm install'
   }
   stage('Run Tests'){
      bat 'npm run api-test'
   }
}
