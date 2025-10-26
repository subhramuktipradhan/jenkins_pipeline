pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                checkout scm
            }
        }

        stage('Extract Data') {
            steps {
                bat "C:\\Users\\Subhra\\AppData\\Local\\Programs\\Python\\Python314\\python.exe extract.py"
            }
        }
    }
}
