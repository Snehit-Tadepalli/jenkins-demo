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
        sh 'git clone https://github.com/Snehit-Tadepalli/jenkins-demo.git'
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
