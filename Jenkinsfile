pipeline {
  agent {
    node {
      label 'ansible_slave'
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