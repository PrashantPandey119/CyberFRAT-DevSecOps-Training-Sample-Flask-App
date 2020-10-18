pipeline {
 agent any
  stages {
   stage ('build docker image'){
    steps {
      sh 'docker build -t cyberfrat:$BUILD_NUMBER .'
      }
     }
    } 
   } 
