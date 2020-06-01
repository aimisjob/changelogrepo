pipeline{
 agent any
 stages{
    stage('build'){
       when{
         changelog '_*some_txt*_'
         }
        steps{
          echo "helloworld changelog"
          }
        }
       }
      }
