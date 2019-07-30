pipeline {
  agent any
  
  git('https://github.com/muditsrivastav16/simple-java-maven-app.git', 'master')
  
  stages {
    stage ('Build') {
      steps {
        echo 'Build'
      }
    }
    stage ('Test') {
      steps {
        echo 'Test'
      }
    }
  }
}
