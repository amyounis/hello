node {
	 def input =  input message: 'chose?', parameters: [choice(choices: 'greeting\nsilence', name: 'choise')]	

	stage ('Compile') {
        
		         
     //   	timeout(time: 20, unit: 'SECONDS') {
       // 		def user = input message: 'who are you ?', parameters: [string(name: 'PERSON', defaultValue: 'Mr Jenkins')]
//		}

		//echo user
		echo input
		
	}
      
	stage ('Test') {
		//	when params.choise == 'greeting'
               		echo "Test"
		
	}
	 
	stage ('Release Build') {
			echo "Release"

	}
}
