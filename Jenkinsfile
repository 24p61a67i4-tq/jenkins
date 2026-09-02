pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                bat '"C:\\Users\\vaibh\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" main.py'
            }
        }
    }
}
