pipeline {
  agent any
    stages {
      stage ("build") {
        steps {
          echo 'building automation pipeline'
          sh './gradlew build'
          archieveArtifacts artifacts: 'dist/trainSchedule.zip'
        }
      }
    }
}
