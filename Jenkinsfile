#!groovy
pipeline {
    agent any

    stages {
        stage('Build 1') {
            steps {
              build 'A - cat file'
              input 'Proceed or Abort?'
            }
          }
        stage('Build 2') {
            steps {
              build 'B - Replace as with bs'
              input 'Proceed or Abort?'
            }
          }
        stage('Build 3') {
            steps {
              build 'C - Replace cs with ds'
            }
        }
    }
}
