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
              stage('Test1') {
                  step {
                sh '''
                sleep 5
                echo This is the first stage: TEST1
                '''
            }
        }
              stage('Test2') {
                  step {
                sh '''
                sleep 5
                echo This is the first stage: TEST2
                '''
            }
        }
              stage('Test3') {
                  step {
                sh '''
                sleep 5
                echo This is the first stage: TEST3
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


