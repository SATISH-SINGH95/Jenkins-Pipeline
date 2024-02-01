pipeline{

    agent any

    stages{
        stage('compile'){
            steps{
                bat 'javac Main.java'
            }
        }
        stage('run'){
            steps{
                bat 'java Main'
            }
        }
    }
}
