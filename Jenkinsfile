pipeline {
    agent any

    stages{

        stage('Git'){
            steps{
                echo 'Test git'
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'SSH_Github_Azure', url: 'git@github.com:ChocTitans/Sprinboot_Devops.git']]])	

            }
        }
        







    }
}