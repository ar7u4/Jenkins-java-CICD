pipeline {

    agent any

    stages {
         
        stage('Git Checkout') {
            steps {
            gitCheckout(
                branch: "main",
                url: "https://github.com/ar7u4/Jenkins-java-CICD.git"
            )
            }
        }

    }

}
