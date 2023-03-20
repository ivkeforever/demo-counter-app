pipeline{
    agent any

    stages {
        stage('Git Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/ivkeforever/demo-counter-app.git'
            }
        }

        stage('Unit Testing') {
            steps {
                sh 'mvn test'
            }
        }
    }
}