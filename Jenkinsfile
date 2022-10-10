pipeline {
  agent any
  stages {
    stage('Before build') {
      steps {
        sh 'echo Before Build'
      }
    }
    stage('Build') {
      steps {
        git 'https://github.com/Snehit-Tadepalli/jenkins-demo'
        sh 'script.sh'
      }
    }
    stage('After build') {
      steps {
        sh 'echo After Build'
      }
    }
  }
}
