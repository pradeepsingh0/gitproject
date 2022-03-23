pipeline {
  agent any
  stages {
    stage('git clone') {
      parallel {
        stage('git clone') {
          steps {
            git(url: 'https://github.com/pradeepsingh0/gitproject.git', branch: 'master')
          }
        }

        stage('tool') {
          steps {
            tool(name: 'maven3.8', type: 'maven3.8')
          }
        }

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