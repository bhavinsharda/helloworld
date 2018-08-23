pipeline {
    agent any
      stages {
        stage('Build') {
            steps {
                bat 'npm install'
            }
        }
        stage('Deploy') {
            steps {
                bat 'NODE_PORT=6978 node ./app.js'
            }
        }  
    }
}
