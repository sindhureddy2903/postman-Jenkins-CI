pipeline {
 agent any
 stages {
   stage('automation') {
     docker.image('postman//newman_alpine33').inside("--entrypoint='['']'") {
      sh "newman --version"
     }
   }
}
}

