pipeline {
    agent any
    stages{
        stage('Create Cloudformation Stack') {
            steps {
                script {
                    sh "aws cloudformation create-stack --stack-name RanveerCloudformation --template-body file://ec2.yaml --region us-east-1"
                }
            }
        }
    }
}