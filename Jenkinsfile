pipeline {
    agent any
    environment {
        no_port = '8565'
      }
      stages {
          stage('Deploy') {
            steps {
                bat 'npm install'
                bat 'node ./app.js'
            }
        }  
    }
}
