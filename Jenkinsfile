pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        sh 'sh "./gradlew compileJava"'
      }
    }

    stage('Unit test') {
      steps {
        sh './gradlew test'
        sh 'sh "./gradlew test"'
      }
    }

  }
}