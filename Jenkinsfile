pipeline {
    agent any
    tools {
        go 'go-1.17'
    }
    environment {
        G0111MODULE='on'
    }
    stages {
        stage('Test') {
            steps {
            git 'https://github.com/AdminTurnedDevOps/go-webapp-sample.git' 
            sh 'go test./...'
          }
        }
    }
}
