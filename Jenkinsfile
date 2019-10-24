pipeline {
  agent {
    docker {
      image 'hashicorp/terraform:latest'
      args '--entrypoint="" -u root -v /opt/jenkins/.aws:/root/.aws'
    }

  }
  stages {
    stage('Init Infra') {
      parallel {
        stage('Init Infra') {
          steps {
            echo 'Starting init Terraform'
          }
        }
        stage('step1') {
          steps {
            echo 'step1'
          }
        }
      }
    }
    stage('Log') {
      steps {
        echo 'sasa'
        echo 'Slut'
      }
    }
  }
}