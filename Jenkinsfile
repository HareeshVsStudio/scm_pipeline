pipeline{
    agent none
stages ('label none'){
    stage{
        steps{
            agent {
                label 'docker-slave'
            }
            echo "This is a agent none pipeline"
            sh "hostname -i"
        }
    }
    stage{
        steps{
            agent{
                label 'docker-slave2'
            }
            echo "This is a agent none pipeline"
            sh "hostname -i"
        }
    }

}
}
