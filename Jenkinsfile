node {
	 def input =  input message: 'chose?', parameters: [choice(choices: 'abdo\nmohammed', name: 'choise')]	

	stage ('Compile') {
        
		         
     //   	timeout(time: 20, unit: 'SECONDS') {
       // 		def user = input message: 'who are you ?', parameters: [string(name: 'PERSON', defaultValue: 'Mr Jenkins')]
//		}

		//echo user
		echo "hello"
		
	}
      
	stage ('Test') {
		if input == 'abdo' {
			do echo "abdo is chosen"
			else echo "abdo is not chosen" 
			}
		
	}
	
	stage ('Release Build') {
			echo "chose abdo"

	}
}
