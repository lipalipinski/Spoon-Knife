pipeline {
  
  agent any
  
  stages {
    
    stage("build") {
      steps {
        sh 'echo "build starts..."'
        sh 'sleep 10'
        sh 'echo "build finished!"'
      }
    }
    
    stage("test") {
      steps {
        sh 'echo "test starts..."'
        sh 'sleep 10'
        sh 'echo "test finished!"'
      }
    }
    
    stage("deploy") {
      steps {
        sh 'echo "deployment starts..."'
        sh 'sleep 10'
        sh 'echo "deployment finished!"'
      }
    }
  }
}
