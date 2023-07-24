pipeline {
    agent any

    stages {

        stage('Git Checkout') {

            steps {
                script {
                    git branch: 'main', url: 'https://github.com/hoanDK0110/golang-web.git'
                }
                
            }
        }
    }
}