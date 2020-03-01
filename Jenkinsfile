pipeline {
  agent any
  stages{
    stage ('Build') {
      steps {
        echo 'Running build autmation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchdeule.zip'
      }
    }
  }
}
