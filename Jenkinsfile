pipeline{
    agent any
    stages{
        stage("Prepare"){
            steps{
            bat "npm install"
            }
        }
        stage("Test"){
            sh "npm run test-unit"

        }   
    }
}