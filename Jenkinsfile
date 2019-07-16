pipeline {
  agent {
    node {
      label 'ansible_worker'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh '''ansible all -m ping
'''
      }
    }
  }
}