pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'BUILD SUCCESS'
          }
        }
        stage('compile') {
          steps {
            sh 'mvn compile'
          }
        }
      }
    }
  }
}