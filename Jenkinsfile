pipeline {
  agent any
  stages {
    stage ('shell') {
      steps {
        git branch: 'shell-script', url:'https://github.com/SatyashreePattanaik/docker-final_task.git'
        sh 'bash shell.sh'
      }
    }
      stage ('python') {
      steps {
        git branch: 'python', url:'https://github.com/SatyashreePattanaik/docker-final_task.git'
        sh 'python3 python.py'
  }
}
