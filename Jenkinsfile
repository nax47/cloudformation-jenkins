pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name jenkins-pipeline-s3bucket --template-body file://s3cft.json --region 'us-east-1'"
              }
             }
            }
            }
