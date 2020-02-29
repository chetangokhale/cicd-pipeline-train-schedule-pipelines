pipeline {
  agent any
    stages {
      stage {
        steps {
        echo 'Build automation step'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts 'dist/trainSchedule.zip'
        }
      }
    }
}
