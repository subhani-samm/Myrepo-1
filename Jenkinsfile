pipeline {
    agent any
    stages{
        stage('Git clone'){
            steps{
                git branch: 'main', url: 'https://github.com/shazforiot/Samplefirstproject.git' 
            }
        }
        
        stage('Test'){
            steps{
                git branch: 'main', url: 'https://github.com/shazforiot/Samplefirstproject.git' 
            }
        }
        
        stage('Build'){
            steps{
                echo " BUILD COMPLETED" 
            }
        }
    }
    
}
