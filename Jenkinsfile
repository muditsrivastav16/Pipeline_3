pipeline {
  agent any  
  stages {
    stage ('Build') {
      steps {
        git('https://github.com/muditsrivastav16/simple-java-maven-app.git', 'master')
        
      }
    }
    stage ('Test') {
      steps {
        echo 'Test'
      }
    }
  }
}
