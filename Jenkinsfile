pipeline {
  agent {
    label 'python3-agent'  // Replace with the label of your Python 3 agent
  }

  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('hello') {
      steps {
        sh 'python3 hello.py'
      }
    }
  }
}
