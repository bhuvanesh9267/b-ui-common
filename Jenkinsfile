pipeline {
    agent any
    stages {
        stage('create stack') {
            steps {
                sh "aws cloudformation create-stack --stack-name ECR --template-body file://template.yaml --region 'ap-south-1'"
            }
        }
    }
}
