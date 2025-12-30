pipeline{
    agent any
    stages{
        stage('one'){
            steps{
              sh 'cat message.txt'
            }
        }
        stage('two'){
            steps{
                sh '''
                pwd
                ls
                '''
            }
        }
        stage('three'){
            steps{
                sh '''
                git branch
                git log -1
                '''
            }
        }
    }
}