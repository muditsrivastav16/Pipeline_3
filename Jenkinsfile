pipeline {
  agent any
  
  scm {
    git {
      remote {
        url 'https://github.com/muditsrivastav16/simple-java-maven-app.git'
      }
      branch 'master'
    }
  }
  
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
