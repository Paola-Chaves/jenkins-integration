pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                sh 'echo One line command'
            }
        }
        stage('Progress'){
            steps{
                sh '''
                    echo Hello
                    echo World
                    echo Testing
                '''
               
            }
        }
    }
}
