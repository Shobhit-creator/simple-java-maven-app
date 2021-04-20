pipeline{
    agent none
    stages{
        stage('download')
        {
            agent{
                     label 'myslavenode'
            }
            steps{
                echo 'my fix123 branch'
            }
        }
    }
}
