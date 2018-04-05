pipeline {
  agent {
    node {
      label 'master1'
    }
    
  }
  stages {
    stage('Git CheckOut') {
      steps {
        git(url: 'https://github.com/garywh/creating-a-pipeline-in-blue-ocean.git', branch: 'master', changelog: true, poll: true, credentialsId: '99')
      }
    }
  }
}
