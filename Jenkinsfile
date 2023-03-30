pipeline {
  
  agent any
  
  stages {
    
    stage("build") {
      steps {
        echo 'build starts...'
        sh 'sleep 10'
        echo 'build finished!'
      }
    }
    
    stage("test") {
      steps {
        echo 'test starts...'
        sh 'sleep 10'
        echo 'test finished!'
      }
    }
    
    stage("deploy") {
      steps {
        echo 'deployment starts...'
        sh 'sleep 10'
        echo 'deployment finished!'
      }
    }
  }
}
