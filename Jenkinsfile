pipeline {
  agent any
  stages {
    stage ('Building re baba') {
      steps {
       echo 'Building test automation'
       sh './gradlew build --no-daemon'
       archiveArtifacts Artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
