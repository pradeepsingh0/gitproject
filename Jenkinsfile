pipeline {
  agent any
  stages {
    stage('git clone ') {
      steps {
        git 'https://github.com/pradeepsingh0/gitproject.git'
        sh 'mvn compile'
      }
    }

  }
  tools {
    maven 'maven3.8'
  }
}