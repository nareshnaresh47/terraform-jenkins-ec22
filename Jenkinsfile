pipeline {
    agent any


    
    environment {
       
        
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
