pipeline {
  agent any
  stages {
    stage('clean workspace ') {
      steps {
        echo 'Hello'
      }
    }
    stage('clean war') {
      steps {
        sh 'mvn clean'
      }
    }
    stage('build') {
      steps {
        sh 'mvn install'
      }
    }
  }
}