agent {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Running building automation'
        sh './gradlew build --no-daemon'
        archivearthifacts arthifacts: 'dist/trainschedule.zip'
      }
    }
  }
}
