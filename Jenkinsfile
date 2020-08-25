pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
                cd /root/terraform
                terraform init
            }
        }
    }
}
