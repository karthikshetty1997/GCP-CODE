pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'terraform --version'
      }
    }

  }
  environment {
    Version = 'Terraform'
  }
}