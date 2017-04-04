#!groovy
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
              build'A - cat file'
              build'B - Replace as with bs'
              build'C - Replace cs with ds'
            }
        }
    }
}
