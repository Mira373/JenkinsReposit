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
            sh '''cd C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\JenkinsReposit_main\\Mock
mvn compile test package'''
          }
        }

      }
    }

  }
}