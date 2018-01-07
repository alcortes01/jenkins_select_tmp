pipeline {
  agent { docker 'ruby' }
  stages {
    stage('build') {
      steps {
        sh 'ruby --version'
        sh 'pwd'
        sh 'touch HolaAlberto'
        sh 'find / -name HolaAlberto'
      }
    }
  }
}
