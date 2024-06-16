pipeline {
  agent any
  options { checkoutToSubdirectory('somedir') }
  stages {
    stage("checkout") {
       steps {
         sh 'touch file1'
      }
   }
  }
}
