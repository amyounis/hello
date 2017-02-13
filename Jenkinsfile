pipeline {
    agent any
    
timeout(time: 15, unit: 'SECONDS') {
        input message: 'Do you want to release this build?',
              parameters: [[$class: 'BooleanParameterDefinition',
                            defaultValue: false,
                            description: 'Ticking this box will do a release',
                            name: 'Release']]
    }

    stages {
        stage('Example') {
            steps {
                echo " hello"
         //       echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
    }
}
