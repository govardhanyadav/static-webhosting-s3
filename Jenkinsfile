pipeline {
    agent any
    stages {
        stage('deploy') {
            steps {
              sh "AWS_DEFAULT_REGION=US East (N. Virginia) us-east-1" 
              sh "AWS_ACCESS_KEY_ID=AKIAT37OMGXCY22PDCFE"  
              sh "AWS_SECRET_ACCESS_KEY=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"
              sh "aws s3 cp Code/index.html s3://suvarna"
            }
        }
    }
}
