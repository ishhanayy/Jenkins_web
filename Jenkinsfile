pipeline{
    agent any
    stages{
        stage("checkout"){
            steps{
                echo "this is the checkout stage"
                bat "mvn clean"
            }
        }
        stage("build"){
            steps{
                echo "this is the build stage"
                bat "mvn compile"
            }
        }

        stage("Deploy"){
            steps{
                echo "this is the deploy stage"
            }
        }
    }
}