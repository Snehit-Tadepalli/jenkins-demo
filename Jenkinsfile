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
        sh 'rm -rf jenkins-demo'
        sh 'git clone https://github.com/Snehit-Tadepalli/jenkins-demo.git'
        sh 'bash script.sh'
      }
    }
    stage('After build') {
      steps {
        sh 'echo After Build'
      }
    }
  }
}
