currentBuild.displayName = "phpApplication-#"+currentBuild.number

pipeline {
    
    
    agent any
    
    stages {
        stage('Cloning Git') {
            steps {
                script{
                echo "Cloning from Git"
                checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/HarpreetSingh18/phpApplication']]])
                }
            }
        }
        
        stage('Create a docker image') {
            steps {
                script{
                echo "Creating Docker Image"
                }
            }
        }
        
        stage('Deploy Application') {
            steps {
                script{
                echo "Deploying the docker Application"
                }
            }
        }
    }
        
        

    
}
