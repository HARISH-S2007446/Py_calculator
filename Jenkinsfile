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
                bat 'python calculator.py'
            }
        }
    }
}