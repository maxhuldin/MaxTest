pipeline {
    agent { label 'agent1' }
    stages {
        stage('Build') {
            steps {
                    withEnv(['PATH+EXTRA=/usr/sbin:/usr/bin:/sbin:/bin']) {  
                    sh 'dotnet build'
                    }
                }
        }
        }
    }
