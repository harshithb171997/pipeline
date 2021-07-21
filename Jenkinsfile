pipeline {
			agent any  
	parameters {
		choice(name: 'TARGET_ENV', choices: ['test','prod'.'har'], description: 'Target environment to deploy')
						   }
						   environment {
							   DEPLOY_TO = "${TARGET_ENV}"
						   }
}
