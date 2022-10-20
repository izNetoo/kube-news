pipeline{
    agent any

    stages{

        stage('Build Docker Image'){
            steps{
                script{
                    dockerapp = docker.build("iznetoo/kube-news:latest", '-f ./src/Dockerfile, ./src')
                }
            }
        }

    }

}