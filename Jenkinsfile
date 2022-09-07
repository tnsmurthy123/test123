pipeline {
  agent any
  stages {
    stage('STAGE1') {
      steps {
        echo 'This is the build number: $BUILD_NUMNER with demo $DEMO'
      }
    }

  }
  environment {
    DEMO = '2'
  }
}