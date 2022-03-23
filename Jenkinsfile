currentBuild.displayName = "phpApplication-#"+currentBuild.number

pipeline {
    
    
    agent any
    
    stages {
        
        
        stage('Create a docker image') {
            steps {
                
                 sh " docker ps" 
                
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
