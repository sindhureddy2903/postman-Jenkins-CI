pipeline {
 node('docker'){
     docker.image('postman//newman_alpine33').inside("--entrypoint='['']'") {
      sh "newman --version"
     }
   }
}


