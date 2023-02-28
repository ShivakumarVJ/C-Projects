pipeline {
    agent any
    stages{
        stage('access') {
            steps{
                sh '''
                sleep 4
                echo "This is access mode"
                '''
            }
        }
        stage('bulid') {
            steps{
                sh '''
                sleep 5
                echo "This is build stage"
                '''
            }
        }
        stage('Binary creation') {
            steps{
                sh '''
                sleep 6
                echo "This is binary creation mode"
                exit 1
                '''
            }
        }
        stage('Test') {
            steps{
                sh '''
                sleep 7
                echo "This is Test stage"
                '''
            }
        }
        stage('Deploy') { 
            steps{
            sh '''
            sleep 8
            echo "This is deploy stage"
            '''
        }
    }
}
}
