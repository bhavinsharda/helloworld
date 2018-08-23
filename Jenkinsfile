pipeline {
    agent any
    environment {
        node_port = '3000'
      }
      stages {
          stage('Deploy') {
            steps {
                bat 'node ./app.js'
            }
        }  
    }
}
