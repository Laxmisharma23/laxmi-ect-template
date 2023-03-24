pipeline {
agent any 
  stages {
    stage('Build ec2') {
      steps {
        sh "aws cloudformation create-stack --stack-name laxmiec2stackcloud4 --template-body file://ec2-template.yaml --region 'us-east-1'"
      }
    }
  }

}

