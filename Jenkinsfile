pipeline {
  agent any
  stages {
    stage ('build') {
      steps {
        git branch: 'maven', url: 'https://github.com/SatyashreePattanaik/docker-final_task.git'
        sh 'mvn clean install'
      }
    }
  }
}
 
        
      
