pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation'
        sh 'export JAVA_HOME=/path/to/java11'
      }
      stage("test"){
        steps{
          echo 'testing the application'
        }
        stage("deploy"){
          steps {
            echo 'Deploying the application'
          } 
    }
  }
}
