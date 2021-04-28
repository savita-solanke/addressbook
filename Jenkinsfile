pipeline{
    agent any
    stages{
        stage ('compile'){
            steps{
                sh 'mvn compile'
            }
        }
        stage ('test'){
            steps{
                sh 'mvn test'
            }
        }
        stage ('package'){
            steps{
                sh 'mvn package'
            }
        }
        stage ('deploy'){
            steps{
                echo 'mvn deploy'
            }
        }
    }
}
