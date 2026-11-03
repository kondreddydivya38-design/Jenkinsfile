pipeline {
  agent any
  
  stages {
    stage ('Compile') {
      step{
        sh 'javac Helloworld.java'
      }
    }
    
    stage('Run')
    step{
      sh 'java Helloworld '
    }
  }
}
}
