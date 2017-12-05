pipeline {
  agent none
  stages {
    stage('Hello') {
      parallel {
        stage('Hello') {
          steps {
            echo 'Hello'
          }
        }
        stage('Der') {
          steps {
            pwd(tmp: true)
            sh 'hostname -f'
          }
        }
      }
    }
  }
}