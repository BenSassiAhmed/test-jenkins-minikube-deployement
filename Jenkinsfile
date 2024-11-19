pipeline {
    agent any
    stages{
    
    stage('deploy') {
            steps {
                sh ' kubectl get nodes'
                sh 'kubectl create -f deploymentservice.yml'
                sh 'kubectl get all'
               
            }
        }
    }
    
}
