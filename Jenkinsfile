pipeline {
    agent any
    
 input id: 'Proceed1', message: 'Proceed or abort?', parameters: [$class: 'TextParameterDefinition', defaultValue: 'uat', description: 'Environment', name: 'env']
    
    stages {
        stage('Example') {
            steps {
                echo "${env} hello"
         //       echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
    }
}
