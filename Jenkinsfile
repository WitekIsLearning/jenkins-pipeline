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
      }
    }

    stage('Docker Build') {
      steps {
        sh 'docker build -f node-app/dockerfile . -t wekkwekk/node-app'
      }
    }

  }
}