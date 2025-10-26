pipeline{
    agent any{
        stages{
            stage("checkout code"){
                steps{
                    checkout scm
                }
            }
            stage("extract data"){
                bat "C:\\Users\\Subhra\\AppData\\Local\\Programs\\Python\\Python314\\python.exe extract.py"
            }
        }
    }
}