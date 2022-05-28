pipeline {
  agent any 
  tools {
    maven 'my_maven'
    git 'mygit'
  }
  stages {
    stage('Build') {
      steps {
        sh "mvn compile"
      }
    }
    stage('Unit test') {
      steps {
        sh "mvn test"
      }
    }
  }
}
