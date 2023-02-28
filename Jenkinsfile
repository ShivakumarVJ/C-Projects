pipeline {
    agent any
    stages{
        stage('bulid') {
            steps{
                sh '''
                sleep 5
                echo "This is build stage"
                '''
            }
        }
        stage('Test') {
            steps{
                sh '''
                sleep 6
                echo "This is Test stage"
                '''
            }
        }
        stage('Deploy') { 
            steps{
            sh '''
            sleep 7
            echo "This is deploy stage"
            '''
        }
    }
}
}
    
