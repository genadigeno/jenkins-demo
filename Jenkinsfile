pipeline {
  agent any
  stages {
    stage('greetings') {
      steps {
        echo 'Hello from github'
        sh 'echo "Hello from github, this is DEMO: $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1.0'
  }
}