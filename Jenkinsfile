pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build autmoation'
        sh './gradlew build --no_daemon'
        archiveArtifacts artifacts: 'dist-trainSchedule.zip'
      }
    }    
  }  
}  
