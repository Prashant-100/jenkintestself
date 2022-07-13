pipeline
{
    agent any
    stages
    {
        stage('SCM checkout')
        {
            steps
            {
                echo "This is git checkout stage"
                sh 'sleep 5'
            }
            
        }
        stage('build')
        {
            steps
            {
                echo "This is build stage"
                sh 'sleep 5'
            }
        }
        stage('push')
        {
            steps
            {
                echo "This is push stage"
                sh 'sleep 5'
            }
        }
        stage('deploy')
        {
            steps
            {
                echo "This is deployment stage"
                sh 'sleep 5'
            }
        }
    }
}
