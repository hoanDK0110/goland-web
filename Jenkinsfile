pipeline {
    agent any
    stages {
        stage('Clone') {
            step {
                git branch: 'main', changelog: false, poll: false, url: 'https://github.com/hoanDK0110/golang-web.git'
            }
        }
    }
}