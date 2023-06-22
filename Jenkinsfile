
//DECLARATIVE
pipeline {
	agent any
	stages {
		stage ( 'Build') {
			steps {
				echo "Build"			
			}
		}
		stage ( 'Test') {
			steps {
				echo "Test"		
			}
		}
		stage ( 'Integration Test') {
			steps {
				echo "Integration Test"
			}
		}
			
	}post {
		always {
			echo "I'm awesome, I run always"
		}
		Success {
			echo "I run when you are successful"
		}
		Success {
			echo "I run when you are fail"
		}
	}

}
