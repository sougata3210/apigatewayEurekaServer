pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git branch: 'main', credentialsId: 'github', url: 'https://github.com/sougata3210/apigatewayEurekaServer'
            }
        }
    }
}
