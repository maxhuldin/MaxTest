pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                    powershell "cd HelloWorldRazor"
                    powershell "dotnet build"
                    
                }
        }
        }
        post {
        always{
        }
        failure{
            }
        }
    }
