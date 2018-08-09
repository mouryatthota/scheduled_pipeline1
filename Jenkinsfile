pipeline {
	agent any
	triggers {
		cron ('*/1 * * * *')
	}
	stages {
		stage ('build') {
			steps {
				echo 'Hi there, you are in stage 1 build!!' 
			}
		}	
		stage ('prod') {
			steps {
				echo 'Hi, you are in production stage 2'
			}
		}
		stage ('test') {
			steps {
				echo 'Hello, you are testing stage 3'
			}
		}
		
	} 
}

