pipeline{
    agent none
stages {
    stage('slave1'){
        steps{
            agent {
                label 'docker_slave'
            }
            echo "This is a agent none pipeline"
            sh "hostname -i"
        }
    }
    stage('slave2'){
        steps{
            agent{
                label 'docker_slave2'
            }
            echo "This is a agent none pipeline"
            sh "hostname -i"
        }
    }

}
}
