pipeline {
	agent any
	triggers {
		cron ('*/1 * * * *')
	}
	stages {
		stage ('build') {
			steps {
				echo 'Hi there, you are in stage 1 - build!!' 
			}
		}	
		stage ('prod') {
			steps {
				echo 'Hi, you are in stage 2 - prod'
			}
		}
		stage ('test') {
			steps {
				echo 'Hello, you are in stage 3 - test'
			}
		}
		
	} 
}

