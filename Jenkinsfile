pipeline {
  agent any  
  git([url: 'https://github.com/muditsrivastav16/simple-java-maven-app.git'])
  stages {
    stage ('Build') {
      steps {
       
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
