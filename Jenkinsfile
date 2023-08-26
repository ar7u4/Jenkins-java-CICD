pipeline{
  agent any
  parameters{

    choice(name: 'action', choices: 'create\ndelete', description: 'Choose create/Destroy')
    string(name: 'ImageName', description: "name of the docker build", defaultValue: 'javapp')
    string(name: 'ImageTag', description: "tag of the docker build", defaultValue: 'v1')
    string(name: 'DockerHubUser', description: "name of the Application", defaultValue: 'vikashashoke')
  }
  stages{
    stage('Git Checkout'){
        steps{
        gitCheckout(
            git branch: 'main',
            url: 'https://github.com/ar7u4/Jenkins-java-CICD.git'
        )
        }
    }
  }
}
