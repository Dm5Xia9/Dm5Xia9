pipeline {
  agent any
  stages {
    stage('git') {
      steps {
        git(url: 'https://github.com/Dm5Xia9/Dm5Xia9/tree/main', branch: 'main', changelog: true)
      }
    }

  }
}