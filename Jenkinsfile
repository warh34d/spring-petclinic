pipeline {
  agent any
  stages {
    stage('Maven Test') {
      steps {
        echo 'Hello World'
        bat 'C:/maven/bin/mvn.cmd test'
      }
    }
    stage('Maven Install') {
      steps {
        sh 'C:/maven/BIN/mvn install'
      }
    }
  }
}