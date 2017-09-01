pipeline {
  agent any

  stages {
    stage("Setup"){
      steps {
        echo "Hello new branch docker"
        sh "uptime"
      }
    }
    stage("Configure"){
      steps {
        sh "cp Jenkinsfile code.java"
      }
    }
  }
}
