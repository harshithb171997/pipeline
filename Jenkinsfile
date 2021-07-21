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
          parallel {
              stage('TEST1') {
                  steps {
                sh '''
                sleep 5
                echo This is the first stage: TEST1
                '''
            }
        }
              stage('TEST2') {
                  steps {
                sh '''
                sleep 5
                echo This is the first stage: TEST2
                '''
            }
        }
              stage('TEST3') {
                  steps {
                sh '''
                sleep 5
                echo This is the first stage: TEST3
                '''
            }
        }
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


