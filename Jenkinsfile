pipeline {
  agent any
  stages {
    stage ('build') {
      steps {
        git branch: 'maven', url: 'https://github.com/SatyashreePattanaik/docker-final_task.git'
        sh 'mvn clean install'
      }
    }
    stage ('python') {
      steps {
        git branch: 'python', url: 'https://github.com/SatyashreePattanaik/docker-final_task.git'
        sh 'python3 python'
      }
    }
    stage ('shell') {
      steps {
        git branch: 'shell-script', url: 'https://github.com/SatyashreePattanaik/docker-final_task.git'
        sh 'bash shell.sh'
      }
    }
  }
}
 
        
      
