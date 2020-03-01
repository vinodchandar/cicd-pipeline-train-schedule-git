pipeline {
  agent any
  stages{
    stage ('Build') {
      steps {
        echo 'Running build autmation'
        archiveArtifacts artifacts: 'dist/trainSchdeule.zip'
      }
    }
  }
}
