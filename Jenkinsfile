pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name innocito-auto-hyd-stack --template-body file://s3cft.yml --region 'ap-northeast-1'"
              }
             }
            }
            }
