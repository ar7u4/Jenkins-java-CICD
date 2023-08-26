@Library('my-shared-lib') _

pipeline{
    agent any
    
    stages{
        stage('Checkout') {
            steps{
            gitCheckout(
              branch: "main"
              url: "https://github.com/ar7u4/Jenkins-java-CICD.git"
            )
            }    
        }
    }
}
