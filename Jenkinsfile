pipeline {
    agent any

    tools {
        maven 'mymaven' 
    }

    stages{
        stage ('Clean Stage'){
            steps{
                

                    sh 'mvn clean'

                
            }   

        }


        stage ('Install Stage'){
            steps{
                

                    sh 'mvn install'

                
            }   

        }

        stage ('Package Stage'){
            steps{
                

                    sh 'mvn package'

                
            }   

        }        
    }

    
    
}