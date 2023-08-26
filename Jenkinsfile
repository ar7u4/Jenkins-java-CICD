pipeline {
  agent any

  stages {
    stage('Git Checkout') {
        steps {
        gitCheckout()
            git branch: 'main', credentialsId: 'eb5319df-769e-4122-b2b2-26b00289a375', url: 'https://github.com/ar7u4/Jenkins-java-CICD.git'
            
        }
    }
  }

}
