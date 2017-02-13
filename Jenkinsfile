node {
	 def input =  input message: 'chose?', parameters: [choice(choices: 'abdo\mohammed', name: 'choise')]	

	stage ('Compile') {
        
		         
     //   	timeout(time: 20, unit: 'SECONDS') {
       // 		def user = input message: 'who are you ?', parameters: [string(name: 'PERSON', defaultValue: 'Mr Jenkins')]
//		}

		//echo user
		echo "hello"
		
	}
      
	stage ('Test') {
			when { expression { input == 'abdo' } }
			echo input
		
	}
	 
	stage ('Release Build') {
			when { expression { input == 'mohammed' } }
			echo "chose abdo"

	}
}
