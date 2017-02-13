node {
	 parameters {choice(choices: 'greeting\nsilence', name: 'choise')}	

	stage ('Compile') {
        
		         
     //   	timeout(time: 20, unit: 'SECONDS') {
       // 		def user = input message: 'who are you ?', parameters: [string(name: 'PERSON', defaultValue: 'Mr Jenkins')]
//		}

		//echo user
		echo "compilation"
		
			//step 1 checkout master from SCM 
			//checkout scm
			//step 2 compile java
			//sh "${JAVA_HOME}/bin/javac  HelloWorld.java"
	}
      
	stage ('Test') {
		when {
                expression { params.choise == 'greeting' }
            }
        
        echo "Test"
		
			//step 1 run HelloWorld.class
		//	sh "${JAVA_HOME}/bin/java HelloWorld"
		
	}
	 
	stage ('Release Build') {
			echo "Release"
			//step 1
		//	sh "echo done"

	}
}
