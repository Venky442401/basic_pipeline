pipeline {
    agent {
        node {
            label 'agent-test'
        }
    }
    
    stages {
        stage("build"){
            steps{
                echo "building started from git"
            }
        }
        stage("Teting_something"){
            steps{
                echo "Testing running"
            }
        }
    }
    post{
           always {
                echo "run always "
            }
            success {
                echo "job successs"
            }
            failure {
                echo "jon failed"
            }
    }
        
}
    