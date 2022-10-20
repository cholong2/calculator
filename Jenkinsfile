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
        sh 'sh "./gradlew test"'
      }
    }

  }
}