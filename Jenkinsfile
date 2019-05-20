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
        stage('Build With maven') {
          steps {
            powershell 'mvn -B -DskipTests clean package'
          }
        }
      }
    }
  }
}