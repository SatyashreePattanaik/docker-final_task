pipeline {
  agent any
  stages {
    stage ('shell') {
      steps {
        git branch: 'shell-script', url:'https://github.com/SatyashreePattanaik/docker-final_task.git'
        sh 'bash shell.sh'
      }
    }
  }
}
