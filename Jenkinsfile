pipeline {
  agent any
  stages {
        
    stage('Git') {
      steps {
        git 'https://github.com/Hyder2227/easyio.git'
      }
    }
     
    stage('Build') {
      steps {
         echo 'Building the application...'
      }
    }  
            
    stage('Test') {
      steps {
         echo 'Testing the application....'
      }
    }
    
    stage('Deploy') {
      steps {
         echo 'Deploying the application...' 
    }
  }
 }
}
