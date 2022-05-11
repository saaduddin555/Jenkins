
pipeline {

  agent any
  
  stages {

        stage("Build") {

          steps {
            echo 'Building an application.'
          } 
        }
     

        stage("test") {

          steps{
            echo "testing the application..'
          }
        }  

        stage('Production') {

          steps {
            echo 'Deploying the Production app'
          }
        }
  } 
}   
