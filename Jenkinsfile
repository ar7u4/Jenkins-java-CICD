@Library('my-shared-lib') _

pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                // Use the custom Git checkout step from the shared library
                gitCheckout([
                    branch: 'main', // Set the desired branch
                    url: 'https://github.com/ar7u4/Jenkins-java-CICD.git'
                ])
            }
        }
        
    }
    
}
