pipeline {
    agent { label 'agent1' }
    stages {
        stage('Build') {
            steps {
                    powershell "cd HelloWorldRazor"
                    powershell "dotnet build"
                    
                }
        }
        }
    }
