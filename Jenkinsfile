pipeline{
    agent any

    stages{
        stage('checkout'){
            steps{
                echo "Checking out code from GitHub"
    }
        }
        stage('build'){
            steps{
                echo "Building the application"
            }
        }
        stage('test'){
            steps{
                echo "Running tests"
            }
        }
         stage('deploy'){
            steps{
                echo "Deploying to AWS"
            }
         }
    }
}