node {
	stage ('Compile') {
		sh "${JAVA_HOME}/bin/javac  HelloWorld.java"
	}
      
	stage ('Test') {
		sh "${JAVA_HOME}/bin/java HelloWorld"
	}
	 
	stage ('Release Build') {
		sh "echo done"
		}
		
     }
