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
        stage("Run Tests"){
            steps{
                echo "========executing C========"
                bat 'npm test'
            }
        }
    }

}