pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            bat "aws cloudformation create-stack --stack-name s3bucket --template-body file://wordpress.json --region us-east-1"
              }
             }
            }
            }
