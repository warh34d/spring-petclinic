pipeline {
  agent any
  stages {
    stage('Maven Test') {
      steps {
        echo 'Hello World'
        sh 'C:/maven/BIN/mvn test'
      }
    }
    stage('Maven Install') {
      steps {
        sh 'C:/maven/BIN/mvn install'
      }
    }
  }
}