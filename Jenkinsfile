pipeline {
    stage any
    {
        stages
        stage ('bulid') {
            step{
                sh '''
                sleep 5
                echo "This is build stage"
                '''
            }
        }
        stage ('Test') {
            step {
                sh '''
                sleep 6
                echo "This is Test stage"
                '''
            }
        }
        stage('Deploy') { 
            sh '''
            sleep 7
            echo "This is deploy stage"
            '''
        }
    }
}
}
    
