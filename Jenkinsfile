pipeline {
  agent 
  any    }

    stages {
          stage ('Show commit author') 
      {
            steps {
                sh "echo '${env.GIT_LATEST_COMMIT_EDITOR}'"
                  }
                                       
      }
          stage('Build') {
            steps {
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
      
