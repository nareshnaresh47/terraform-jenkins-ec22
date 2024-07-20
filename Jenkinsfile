pipeline {
    agent any


    
    environment {
        AWS_ACCESS_KEY_ID     = "AKIA3V6GUJW5TV3A3CVO"
        AWS_SECRET_ACCESS_KEY = "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"
        TF_IN_AUTOMATION      = '1'
    }

    stages {
        stage('Init and Apply') {
            steps {
              
                sh 'terraform init -input=false'
                    
                sh 'terraform apply -auto-approve'
            }
        }

       
    }


}
