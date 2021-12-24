pipeline {
  agent {
    node {
      label 'WindowsLabel'
    }

  }
  stages {
    stage('Source') {
      steps {
        git 'https://github.com/dhineshaps/twopull.git'
      }
    }

  }
  environment {
    COMPLETED_MSG = 'Build done!'
  }
}