pipeline {
  agent slave1

  stages {
    stage('build') {
      sh 'ant -f build.xml -v'
    }
  }
}
