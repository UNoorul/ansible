pipeline {
  agent any
  stages {
    stage('Dev1') {
      steps {
        echo 'sample text1'
        sleep 2
        git(url: 'https://github.com/UNoorul/ansible', branch: 'master')
      }
    }

    stage('QA') {
      steps {
        echo 'Sample QA'
        sleep 2
      }
    }

  }
}