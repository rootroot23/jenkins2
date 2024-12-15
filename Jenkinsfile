pipeline {
    agent any
    stages {
        stage('integration'){ //c'est la partir integration
            steps{
                sh 'touch integrationt'
            }
        }
        stage('Teste'){ // je fais le teste
            steps{
                sh 'touch fichierlooge.log'
            }
        }
        stage('production'){ // je fais la prooduction
            steps{
                sh 'mkdir pprod'
            }
        }
    }
}
