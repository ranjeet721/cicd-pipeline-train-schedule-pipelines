pipeline {
  agent any
  stages{
    stage{'Build'}{
      steps{
      echo 'Running Build'
      sh './gradlew build --no-daemon'
      archieveArtifacts artifact: 'dist/trainSchedule.zip'
      }
    }
  }

}
