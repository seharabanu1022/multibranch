pipeline{
    agent any
    stages{
        stage("maven build"){
            when{
                branch = "develop"
            }
            steps{
                echo "maven successfully build"
            }
        }
        stage("deploy to dev"){
            when{
                branch = "develop"
            }
            steps{
                echo "deploy to dev"
            }
        }
        stage("deploy to test"){
            when{
                branch = "test"
            }
            steps{
                echo "deploy to dev"
            }
        }
        stage("deploy to prod"){
            when{
                branch = "prod"
            }
            steps{
                echo "deploy to dev"
            }
        }
    }
}