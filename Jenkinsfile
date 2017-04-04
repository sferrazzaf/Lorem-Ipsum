#!groovy
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
              build 'A - cat file'
              input 'Proceed or Abort?'
              build 'B - Replace as with bs'
              build 'C - Replace cs with ds'
            }
        }
    }
}
