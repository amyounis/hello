pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                parameters {string(name: 'Greeting', defaultValue: 'Hello', description: 'How should I greet the world?')}
                echo "${Greeting} hello"
         //       echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
    }
}
