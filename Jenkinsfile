pipeline {
    agent { label 'agent1' }
    environment {
   HOME = '/tmp'
    } 
    stages {
        stage('Build') {
            steps {
                    sh 'dotnet build'
                }
        }
        }
    }
