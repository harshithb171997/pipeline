pipeline {
			agent any  
			stages {
				stage('STAGE1') {						
					         steps {
							 catchError(buildResult: 'SUCCESS',stageResult: 'FAILURE') {
						sh '''
							pwd
							sleep 5
							exit 1
						'''
						 }	
				           }
				}
				stage('STAGE2') {						
					         steps {
						sh '''
							echo stage2 is building
							sleep 5
							
						'''
						 }	
				           }
			}
}
