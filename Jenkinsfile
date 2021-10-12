pipeline {
  agent any
    
  tools {nodejs "NodeJS 16.0.0"}
    
  stages {
        
//     stage('Git') {
//       steps {
//         git 'https://github.com/AnthonyChraim/Autotracks'
//       }
//     }
     
    stage('Build') {
      steps {
        sh 'npm install'
         sh '<<Build Command>>'
      }
    }  
    
            
    stage('Test') {
      steps {
        sh 'node test'
      }
    }
  }
}
