pipeline {
  agent {
    node {
      label '1'
    }
    
  }
  stages {
    stage('clone') {
      steps {
        git(url: 'git@github.com:hhhfly/123.git', branch: 'master')
      }
    }
  }
}