pipeline {
  agent any

  environment{
    RELEASE='20.4'
  }

  stages {
    stage('Build') {
    agent any
    environment {
        LOG_LEVEL= 'IFNO'
    }
      steps {
        echo "Building release ${RELEASE} with log level ${LOG_LEVEL}..."
      }
    }

    stage('Test'){
        steps{
            echo "Testing. I can see release ${RELEASE}, but not log level ${LOG_LEVEL}"
        }
    }

  }

}