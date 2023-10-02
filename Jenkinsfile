pipeline{
    agent any
    stages{
        stage("maven build"){
            when{
                branch  "develop"
            }
            steps{
                echo "maven  build success"
            }
        }
        stage("deploy to dev"){
            when{
                branch "develop"
            }
            steps{
                echo "deploy to dev"
            }
        }
        stage("deploy to test"){
            when{
                branch  "test"
            }
            steps{
                echo "deploy to dev"
            }
        }
        stage("deploy to prod"){
            when{
                branch  "main"
            }
            steps{
                echo "deploy to prod"
            }
        }
    }
}