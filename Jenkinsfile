pipeline {
  agent any 
  stages {
    stage('Build'){
      steps {
        echo 'Running build automtion'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
