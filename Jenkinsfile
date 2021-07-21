pipeline {
			agent any  
			stages {
				stage('STAGE1') {	
					when {
						branch 'master' 
					}
					         steps {
							sh '''
							echo "Build is running"
						'''
						 }	
				           }
			}
}
