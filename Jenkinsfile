pipeline {
    agent any
    environment {
        node_port = '9696'
      }
      stages {
          stage('Deploy') {
            steps {
                bat 'node ./app.js'
            }
        }  
    }
}
