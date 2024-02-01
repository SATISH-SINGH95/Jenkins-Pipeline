pipeline{

    agent any

    stages{
        stage('compile'){
            steps{
                sh 'javac Main.java'
            }
        }
        stage('run'){
            steps{
                echo 'java Main'
            }
        }
    }
}