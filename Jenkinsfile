node {
		
	// stage 1 Compilation
	stage ('Compile') {
        
        
     //   	timeout(time: 20, unit: 'SECONDS') {
        		input message: 'who are you ?',
            		      parameters: [string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')]
//		}

		echo "hello ${params.PERSON}"
		
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
