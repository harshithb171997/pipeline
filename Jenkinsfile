pipeline {
    agent any
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
                  step {
                sh '''
                sleep 5
                echo This is the first stage: TEST1
                '''
            }
        }
              stage('TEST2') {
                  step {
                sh '''
                sleep 5
                echo This is the first stage: TEST2
                '''
            }
        }
              stage('TEST3') {
                  step {
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


