pipeline {
  agent any
  stages {
    stage('greetings') {
      steps {
        echo 'Hello from github'
        sh 'bat "Hello from github, this is DEMO: $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1.0'
  }
}