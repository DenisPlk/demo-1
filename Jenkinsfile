pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'this is a build number $BUILD_NUMBER of $demo'
      }
    }

  }
  environment {
    demo = '1'
  }
}