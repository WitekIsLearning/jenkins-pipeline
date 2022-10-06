pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'build'
      }
    }

    stage('test') {
      steps {
        echo 'test'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy'
        sh 'docker build -f jenkins-pipeline/node-app/dockerfile . -t wekkwekk/node-app'
      }
    }

  }
}