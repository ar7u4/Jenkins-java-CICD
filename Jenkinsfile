@Library('my-shared-lib')

pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
              script {
                gitCheckout(
                  branch: "main"
                  url: "https://github.com/ar7u4/Jenkins-java-CICD.git"
                )
              }    
            }
        }
    }
}
