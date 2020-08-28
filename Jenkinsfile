pipeline {
  agent any
  stages {
    stage('Stage 1') {
      steps {
        sh 'echo "This is build $BUILD_NUMBER of demo $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}