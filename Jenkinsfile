pipeline{
    agent any
    stages{
        stage('source'){
            steps{
                echo "****source code"
            }    
        }
        stage('build'){
            steps{
                echo"**** build code"
            }   
        }
        stage('deploy'){
            steps{
                echo "**** deploy code"
            }
        }
        stage('test'){
            steps{
               echo "**** test code"
            }    
        }
        stage('sonar'){
            steps{
                echo "**** sonar code"
            } 
        }
        stage('docker'){
            steps{
                echo "**** docker code"        
            }
        }
        stage('k8s'){
            steps{
                echo "**** k8s code"
            }
        }
    }
}
