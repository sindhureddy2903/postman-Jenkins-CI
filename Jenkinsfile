pipeline {
 agent any
 stages {
   stage('automation') {
    node('build-tests') {
     docker.image('postman//newman_alpine33').inside("--entrypoint='['']'") {
      sh "newman --version"
     }
   }
 }
}
}

