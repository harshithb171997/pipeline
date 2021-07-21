pipeline {
			agent any  
			stages {
				stage('STAGE1') {	
					when {
						branch 'main' 
					}
					         steps {
							sh '''
							echo "Build is running"
						'''
						 }	
				           }
			}
}
