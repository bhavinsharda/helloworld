pipeline {
    agent any
    environment {
        no_port = '3000'
      }
      stages {
          stage('Deploy') {
            steps {
                bat 'node ./app.js'
            }
        }  
    }
}
