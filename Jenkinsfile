pipeline{
    agent any
    tools{
        npm "NodeJS"
    }
    stages{
        stage('Fetch Code'){
            steps{
                sh 'git clone https://github.com/CharismaticOwl/TravelMemory-with-Jenkins.git'
            }
        }
        stage('Install'){
            steps{
                sh 'cd TravelMemory-with-Jenkins/frontend && npm install'
            }
        }
    }
}