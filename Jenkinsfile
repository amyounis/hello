node {
	
   stages {
	// stage 1 Compilation
	stage ('Compile') {
		
		steps {	
			//step 1 checkout master from SCM 
			checkout scm
			//step 2 compile java
			sh "javac  HelloWorld.java"
		}
	}
      
	// stage 2 Testing
	stage ('Test') {
		
		steps{
			//step 1 run HelloWorld.class
			sh "${JAVA_HOME}/bin/java HelloWorld"
		}
	}
	 
	// stage 3 release artifact on repository
	stage ('Release Build') {
			
		steps {
			//step 1
			sh "echo done"
		}
	}
   }
}




