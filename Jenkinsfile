pipeline {
    agent any
    stages {
        stage('integration'){ //c'est la partir integration
            steps{
                sh 'touch integra4tiont'
            }
        }
        stage('Teste'){ // je fais le teste
            steps{
                sh 'touch fichilooge.log'
            }
        }
        stage('production'){ // je fais la pr1ooduction
            steps{
                sh 'mkdir pprod'
            }
        }
    }
}
