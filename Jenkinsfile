pipeline {
  agent {
    node {
      label 'SonarAndJenkinsSlave'
    }
  }
  
  stages {
    stage('Stage 1') {
      steps {
        echo 'You are in stage 1'
      }
    }
    
    stage('Deploying code') {
      steps {
        echo 'Deployment done'
      }
    }
  }
}
