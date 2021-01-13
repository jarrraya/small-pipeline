pipeline {
  agent 
  any }
  stages {
  
       stage("build")
         {
          agent  {
                docker { image 'node:12-buster-slim' }
                 }
            stages{
                stage ('npm install'){
                    steps {
                        sh "npm install"
                    }
                }
                    echo "building done"
                 }
         }
      stage("test")
        {
               steps
                 {
                    echo "testing done done"
                 }
        }
      stage("deploy")
        {
                  steps
                 {
                    echo "deploying done gj"
                 }
        }
  
  }




}
