pipeline {
  agent any
  stages {
    stage('Stage1') {
      parallel {
        stage('Stage1') {
          steps {
            sh 'echo "Hello Guys"'
            sleep 10
          }
        }

        stage('stage2') {
          steps {
            echo 'Hello from state 2'
          }
        }

      }
    }

  }
}