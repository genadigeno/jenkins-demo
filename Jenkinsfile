pipeline {
  agent any
  stages {
    stage('greetings') {
      steps {
        //bat 'echo "This is demo %DEMO%"'
        bat 'echo "This is build number $BUILD_NUMBER of demo $DEMO"'
            bat '''
               echo "Using a multi-line shell step"
               chmod +x test.sh
               ./test.sh
            '''
      }
    }

  }
  environment {
    DEMO = '1.0'
  }
}
