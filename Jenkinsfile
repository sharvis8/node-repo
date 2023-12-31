pipeline {
  agent any
  stages {
    stage('checkout GITrepo') {
      steps {
        git(url: 'https://github.com/sharvis8/go-app', branch: 'main')
      }
    }

  }
}