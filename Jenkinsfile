pipeline {
 agent any
 
    stages {
         
          stage ('Execute CI pipeline') 
                            {
            agent {
                docker { image 'node' }
                  }
                            }
         stage ('npm install')
     {
                   steps {
                        bat "npm install"
                          }
     }
      
      stage('test') {
                steps {
                    echo 'testing..'
                      }
                     }
      
      stage('deploy')
     {
            steps
                  {
                echo 'deploying..'
                  }
     }
           }
      
}
