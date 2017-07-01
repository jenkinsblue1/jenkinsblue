pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'demo job'
        build 'build'
      }
    }
    stage('compile') {
      steps {
        sh 'echo "i am done"'
      }
    }
  }
}