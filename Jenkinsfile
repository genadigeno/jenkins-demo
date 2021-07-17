pipeline {
  agent any
  stages {
    stage('greetings') {
      steps {
        bat 'echo "This is demo %DEMO%"'
      }
    }

  }
  environment {
    DEMO = '1.0'
  }
}