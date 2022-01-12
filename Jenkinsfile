pipeline {
  agent any
    stages {
      stage ("build") {
        steps {
          echo 'building automation pipeline'
          sh './gradlew build'
          archiveArtifacts artifacts: 'dist/trainSchedule.zip'
        }
      }
    }
}
