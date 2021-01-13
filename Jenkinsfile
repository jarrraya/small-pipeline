pipeline {
  agent 
  any    }

    stages {
        stage ('Show commit author') {
            steps {
                sh "echo '${env.GIT_LATEST_COMMIT_EDITOR}'"
                  }
                                     }c
        stage ('Execute CI pipeline') {
            agent {
                docker { image 'node:12-buster-slim' }
                  }
            stages{
                stage ('npm install'){
                    steps {
                        sh "npm install"
                          }
                  }
                stage('NPM build'){
                    steps {
                        sh 'npm run-script build --prod'
                          }
                }
  
