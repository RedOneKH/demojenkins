pipeline {
  environment {
    PATH = "C:\\Program Files\\Git\\usr\\bin;C:\\Program Files\\Git\\bin;${env.PATH}"
  agent any
  stages {
    stage('compile') {
      steps {
        script {
          sh "mvn compile"
        }

      }
    }
  }
}
