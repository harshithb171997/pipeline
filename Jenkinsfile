pipeline {
    agent { label 'agent1' }
    stages {
        stage('BUILD') {
            steps {
                sh '''
                pwd
                sleep 5
                echo This is the first stage: BUILD
                '''
            }
        }
      stage('TEST') {
            steps {
                sh '''
                pwd
                sleep 5
                echo This is the first stage: TEST
                '''
            }
        }
stage('DEPLOY') {
            steps {
                sh '''
                pwd
                sleep 5
                echo This is the first stage: DEPLOY
                '''
            }
        }
    }
}
