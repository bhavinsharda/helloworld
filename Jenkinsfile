pipeline {
    agent any
      stages {
          stage('Deploy') {
            steps {
                bat '$ NODE_PORT=6978 node ./app.js'
            }
        }  
    }
}
