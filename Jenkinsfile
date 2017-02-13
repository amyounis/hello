pipeline {
    agent any
    
    parameters {
        string(name: 'Greeting', defaultValue: 'Hello', description: 'How should I greet the world?')
    }
    
    stages {
        stage('Example') {
            steps {
                echo "${Greeting} hello"
         //       echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
    }
}
