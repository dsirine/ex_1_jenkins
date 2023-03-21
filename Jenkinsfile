pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh 'cut  -d : -f1,3 /etc/passwd > /tmp/users'
      }
    }

  }
}