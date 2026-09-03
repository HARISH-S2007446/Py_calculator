pipeline{
    agent any
    options{
        skipDefaultCheckout(true)
    }
    stages{
        stage('Checkout Code'){
            steps{
                checkout scm
            }
        }
        stage('Build'){
            steps{
                bat '"C:\Users\desktop\AppData\Local\Programs\Python\Python312\python.exe" calculator.py'
            }
        }
    }
}