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
                sh 'touch fichierloge.log'
            }
        }
        stage('production'){ // je fais la production
            steps{
                sh 'mkdir prod'
            }
        }
    }
}
