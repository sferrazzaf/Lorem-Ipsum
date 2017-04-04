#!groovy
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
              build 'A - cat file'
              input '${JOB_NAME} done. Proceed?'
              build 'B - Replace as with bs'
              build 'C - Replace cs with ds'
            }
        }
    }
}
