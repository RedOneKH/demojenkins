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
            script {
            sh 'mvn compile'
            }
          }
        }
      }
    }
  }
}
