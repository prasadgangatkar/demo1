pipeline {
    agent {
        node {
            label 'slave'
            }
        }
        tools {
            maven '3.6.3'
        }
    stages {
        stage ('clean up') {
            steps {
                echo 'delete dir'
                deleteDir()
            } 
        
        }
    
    }
        }
    
  
