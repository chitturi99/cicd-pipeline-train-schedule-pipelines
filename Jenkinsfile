pipeline 
{
  agent any
  stages{
    stages('build'){
    stage {
      echo 'running build automation'
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainschedule.zip'
    }
  }
}
}