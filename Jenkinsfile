pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
       git([url: 'https://github.com/muditsrivastav16/simple-java-maven-app/', branch: 'master'])        
        batchFile 'mvn clean compile'
      }
    }
    stage ('Test') {
      steps {
        echo 'Test'
      }
    }
  }
}
