pipeline{
    agent any
    options{
        skipDefaultCkeckout(true)
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