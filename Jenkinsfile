pipeline{
    agents any
    stages{
        stage('Fetch Code'){
            steps{
                sh 'git clone https://github.com/CharismaticOwl/TravelMemory-with-Jenkins.git'
            }
        }
        stage('Build Frontend'){
            steps{
                sh '''cd TravelMemory-with-Jenkins/frontend
                    - npm init -y
                    - npm install index.js'''
            }
        }
    }
}