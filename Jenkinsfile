pipeline {
    agent any
    environment {
        node_port = '6978'
      }
      stages {
          stage('Deploy') {
            steps {
                bat 'node ./app.js'
            }
        }  
    }
}
