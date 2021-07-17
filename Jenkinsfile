pipeline {
  agent any
  stages {
    stage('greetings') {
      steps {
        //bat 'echo "This is demo %DEMO%"'
        bat 'echo "This is build number %BUILD_NUMBER% of demo %DEMO%"'
        
      }
    }

  }
  environment {
    DEMO = '1.0'
  }
}
