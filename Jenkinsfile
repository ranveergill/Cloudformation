pipeline {
    agent any
    stages {
        stage('Create Stack') {
            steps {
sh "aws cloudformation create-stack --stack-name ranveerCloud --template-body file://ec2.yaml --region us-east-1"
                
            }
        }
    }
}