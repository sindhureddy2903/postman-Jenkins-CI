node {
   stage('Postman Jenkins CI'){
      git 'https://github.com/sindhureddy2903/postman-Jenkins-CI.git'
   }
   stage('Install Node Dependencies'){
      sh 'npm install'
   }
   stage('Run Tests'){
      sh 'npm run api-test'
   }
}
