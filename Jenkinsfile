pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        script {
          bat "mvn compile"
        }

      }
    }
  }
  environment {
    PATH = "C:\\Program Files\\Git\\usr\\bin;C:\\Program Files\\Git\\bin;${env.PATH}"
  }
}
