pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                    powershell "cd HelloWorldRazor 
                    dotnet build"
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
}
