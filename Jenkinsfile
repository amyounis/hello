node {
		
	// stage 1 Compilation
	stage ('Compile') {
		
			//step 1 checkout master from SCM 
			checkout scm
			//step 2 compile java
			sh "${JAVA_HOME}/bin/javac  HelloWorld.java"
		
	}
      
	// stage 2 Testing
	stage ('Test') {
		
			//step 1 run HelloWorld.class
			sh "${JAVA_HOME}/bin/java HelloWorld"
		
	}
	 
	// stage 3 release artifact on repository
	stage ('Release Build') {
			
			//step 1
			sh "echo done"

	}
}
