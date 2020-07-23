pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            bat "aws cloudformation create-stack --stack-name tpcswordpress --template-body file://wordpress.json --region us-east-1 --parameters ParameterKey=KeyName,ParameterValue=awsdemo ParameterKey=InstanceType,ParameterValue=t2.micro ParameterKey=DBUser,ParameterValue=sqladmin ParameterKey=DBPassword,ParameterValue=Password123 ParameterKey=DBRootPassword,ParameterValue=Password123"
              }
             }
            }
            }
