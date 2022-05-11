
pipeline {

  agent any
  
  stages{
    
    stage("Build") {

      steps {
       echo 'Building an application..'
      } 
    }
     
    stage("Test") {
    
      steps {
        echo 'testing the application..'
      }
    }  

    stage("Production") {

      steps {
        echo 'Deploying the Production app..'
      }
    }
  } 
}   
