pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                // Clean workspace before checking out
                deleteDir()
                
                // Clone the GitHub repository
                checkout([
                    $class: 'GitSCM',
                    branches: [[name: '*/main']], // You can change the branch as needed
                    doGenerateSubmoduleConfigurations: false,
                    extensions: [],
                    submoduleCfg: [],
                    userRemoteConfigs: [[
                        // credentialsId: 'YOUR_GITHUB_CREDENTIALS_ID', // Replace with your GitHub credentials ID
                        url: 'https://github.com/ar7u4/Jenkins-java-CICD.git'
                    ]]
                ])
            }
        }
