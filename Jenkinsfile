pipeline{
	agent any
	
	
	stages {
		stage ("Checkot stage"){
			steps {
				sh echo 'This is checkout stage'
			}
		
		}
	
		stage ("Test stage"){
			steops {
				sh echo 'this is  test stage'
			
			}

		}
		
		stage ("Build stage"){
			steps {
				sh echo 'this is build stage'
			}
		
		}
		stage ("Push to docker") {
			steps {
				sh 'echo deployed to docker'
			
			}
		
		
		}
	
	}

}
