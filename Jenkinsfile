pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'jenkins/build.sh'
      }
    }

    stage('Test') {
      steps {
        sh 'jenkins/test-all.sh'
      }
    }

    stage('Deploy') {
      steps {
        sh 'jenkins/deploy.sh'
      }
    }

  }
}