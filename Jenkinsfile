pipeline {
  agent { docker "maven:3-alpine" }

  stages {
    stage('maven') {
      steps {
        sh "mvn -version"
        sh "java -version"
      }
    }
  }
}
