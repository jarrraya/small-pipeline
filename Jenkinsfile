pipeline {
  agent   any    

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
