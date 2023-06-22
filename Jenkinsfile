
//DECLARATIVE
pipeline {
	//agent any
	agent { docker { image 'rcschandrasekhar/hello-world-nodejs:0.0.2.RELEASE'}}
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
			
	}

	post {
		always {
			echo 'Iam awesome I run always'
		}

		success {
			echo 'I run when you are successful'
		}

		failure {
			echo 'I run when you are fail'
		}
	}

}
