pipeline {
  agent { docker { image 'node:14-alpine' } }

    stages {
         
          stage('Build') {
            steps {
              bat 'make'
                echo 'Building..'
            }
          }
        
      
      stage('test') {
            steps {
                echo 'testing..'
            }
        }
      
      stage('deploy') {
            steps {
                echo 'deploying..'
            }
        }
    }
      
}
