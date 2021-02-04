pipeline {
  agent any
  stages {
    stage {'Build'} {
      steps {
        echo 'Runny Build Automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
