node {
		
	// stage 1 Compilation
	stage ('Compile') {
        
        
        timeout(time: 15, unit: 'SECONDS') {
        input message: 'Do you want to release this build?',
              parameters: [[$class: 'BooleanParameterDefinition',
                            defaultValue: false,
                            description: 'Ticking this box will do a release',
                            name: 'Release']]
    }
} catch (err) {
    def user = err.getCauses()[0].getUser()
    echo "Aborted by:\n ${user}"
}

    echo "compilation"
		
			//step 1 checkout master from SCM 
			//checkout scm
			//step 2 compile java
			//sh "${JAVA_HOME}/bin/javac  HelloWorld.java"
		
	}
      
	// stage 2 Testing
	stage ('Test') {
        
        echo "Test"
		
			//step 1 run HelloWorld.class
		//	sh "${JAVA_HOME}/bin/java HelloWorld"
		
	}
	 
	// stage 3 release artifact on repository
	stage ('Release Build') {
			echo "Release"
			//step 1
		//	sh "echo done"

	}
}
