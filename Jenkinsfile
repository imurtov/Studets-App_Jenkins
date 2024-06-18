pipeline{
    agent any
    stages{
        stage("NPM Instal"){
            steps{
                echo "========executing A========"
                bat 'npm install'
            }
        }
        stage("NPM Audit"){
            steps{
                echo "========executing B========"
                bat 'npm audit'
            }
        }
    }

}