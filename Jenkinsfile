pipeline {
    agent any
    environment {
        NODE_PORT = '6978'
      }
      stages {
          stage('Deploy') {
            steps {
                bat 'node ./app.js'
            }
        }  
    }
}
