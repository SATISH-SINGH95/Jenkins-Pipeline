pipeline{

    agent any

    stages{
        stage("compile"){
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

    post{
        always{
            echo 'Always message always be displayed'
        }

        success{
            echo 'This message will be displayed after successful execution of each stages'
        }

        failure{
            echo 'This message will be displayed if any of stages failed to execute'
        }
    }
}
