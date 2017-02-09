node {
	stage ('Compile') {
		checkout scm
		sh "javac  HelloWorld.java"
	}
      
	stage ('Test') {
		sh "${JAVA_HOME}/bin/java HelloWorld"
	}
	 
	stage ('Release Build') {
		sh "echo done"
		}
		
     }



