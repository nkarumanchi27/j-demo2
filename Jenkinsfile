pipeline {
  agent any
  stages {
    stage('Stage1') {
      parallel {
        stage('Stage1') {
          steps {
            sh 'echo "Hello Guys"'
            sh 'echo "I am added in the pipeline file"'
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