pipeline {
  agent any
  tools {
      jdk 'Jdk8'
      maven 'Maven'
  }
  stages {
      stage('test java installation') {
          steps {
              sh 'java -version'               
          }
      }
      stage('test maven installation') {
          steps {
              sh 'mvn -version'           
          }
      }
  }
}