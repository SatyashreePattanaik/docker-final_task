pipeline {
  agent any
  stages {
    stage ('python') {
      steps {
        git branch: 'python', url: 'https://github.com/SatyashreePattanaik/docker-final_task.git'
        sh 'python3 python.py'
      }
    }
  }
}
 
        
      
