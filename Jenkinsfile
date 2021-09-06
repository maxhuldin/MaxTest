pipeline {
    agent { label 'agent1' }
    environment {
   DOTNET_CLI_HOME = "/tmp/DOTNET_CLI_HOME"
    } 
    stages {
        stage('Build') {
            steps {
                    sh 'dotnet build'
                }
        }
        }
    }
