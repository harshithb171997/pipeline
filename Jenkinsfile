pipeline {
    agent any
    stages {
        stage('BUILD') {
            agent { label 'agent1' }
            steps {
                sh '''
                pwd
                sleep 5
                echo This is the first stage: BUILD
                '''
            }
        }
      stage('TEST') {
          agent { label 'agent2' }
            steps {
                sh '''
                pwd
                sleep 5
                echo This is the first stage: TEST
                '''
            }
        }
stage('DEPLOY') {
    agent { label 'agent1' }
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
