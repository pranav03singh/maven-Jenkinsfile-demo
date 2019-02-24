pipeline {
    agent any

    stages{
        stage ('Clean Stage'){
            steps{
                withMaven(maven: 'mymaven'){

                    sh 'mvn clean'

                }
            }   

        }


        stage ('Install Stage'){
            steps{
                withMaven(maven: 'mymaven'){

                    sh 'mvn install'

                }
            }   

        }

        stage ('Package Stage'){
            steps{
                withMaven(maven: 'mymaven'){

                    sh 'mvn package'

                }
            }   

        }        
    }

    
    
}