pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/segbeyon24/node-todo', branch: 'main')
        git(url: 'https://github.com/segbeyon24/node-todo', branch: 'master')
      }
    }

  }
}