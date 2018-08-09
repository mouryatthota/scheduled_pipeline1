pipeline {
	agent any
	triggers {
		cron ('H/1 * * * *')
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
		
	} 
}

