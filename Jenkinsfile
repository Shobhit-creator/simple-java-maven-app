pipeline{
    agent none
    stages{
        stage('download')
        {
            agent{
                     label 'myslavenode'
            }
            steps{
                echo 'my master branch'
            }
        }
    }
}
