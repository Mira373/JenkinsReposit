pipeline {
  agent any
  stages {
    stage('Log Maven Version') {
      parallel {
        stage('Log Maven Version') {
          steps {
            sh 'mvn --version'
          }
        }

        stage('Build Maven Project') {
          steps {
            sh '''mvn -f Mock/pom.xml package
mvn compile package'''
          }
        }

      }
    }

  }
}