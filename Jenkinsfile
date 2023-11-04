pipeline {
  agent any
  options { checkoutToSubdirectory('somedir') }
  stages {
    stage("checkout") {
       steps {
         sh 'echo hello world'
      }
   }
  }
}
