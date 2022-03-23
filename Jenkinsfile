pipeline {
  agent any
  stages {
    stage('git clone') {
      steps {
        git(url: 'https://github.com/pradeepsingh0/gitproject.git', branch: 'master')
      }
    }

    stage('run a command') {
      steps {
        sh 'mvn install'
        sh 'mvn install'
      }
    }

  }
}