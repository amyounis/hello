pipeline {
  agent none
  stages {
    stage('Compile') {
      steps {
        parallel(
          "Compile": {
            sh '${JAVA_HOME}/bin/javac  HelloWorld.java'
            sh 'echo new step'
            
          },
          "newstage": {
            sh 'echo "where is this stage"'
            
          }
        )
      }
    }
    stage('Test') {
      steps {
        sh '${JAVA_HOME}/bin/java HelloWorld'
      }
    }
    stage('Release') {
      steps {
        sh 'echo Release'
      }
    }
  }
  environment {
    JAVA_HOME = '/usr/local/jdk1.8.0_121'
  }
}
