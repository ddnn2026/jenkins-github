pipeline{
    agent any
    stages{
        stage('Greeting'){
            steps{
                echo "Greeting"
            }
        }
        stage('Clone'){
            steps{
                git 'https://github.com/ddnn2026/jenkins-github.git'
            }
        }
    }
}
//change