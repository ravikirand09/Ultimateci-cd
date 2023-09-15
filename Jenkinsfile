pipeline{
    agent any
    stages{
        stage("Git checkout"){
            steps{
                git 'https://github.com/ravikirand09/Ultimateci-cd.git'
            }

        stage("Unit test"){
            steps{
                sh 'mvn test'
            }
        }


        }
    }
}