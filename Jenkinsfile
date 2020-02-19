pipeline {
  agent any
  stages {
    stage('ks') {
      parallel {
        stage('ks') {
          steps {
            sh 'echo "heloo world"'
          }
        }

        stage('kd') {
          steps {
            sh 'echo "second step"'
          }
        }

        stage('kf') {
          steps {
            sh 'echo "hi"'
          }
        }

      }
    }

  }
}