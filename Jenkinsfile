pipeline
   agent any
      stages{
          stage('Build'){
              steps{
                  echo 'Building...' 
              }
          }
           stage('Test'){
               steps{
                   echo 'Testing...'
               }
           }
           stage('Deploy'){
               stage{
                   echo 'Deploying the code..'
               }
           }
          }
      }