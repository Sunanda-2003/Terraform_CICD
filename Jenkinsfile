pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                git branch: 'main', url: 'https://github.com/Sunanda-2003/Terraform_CICD.git'
            }
        }
        stage('init') {
            steps {
                sh 'terraform plan'
            }
        }
    }
}
