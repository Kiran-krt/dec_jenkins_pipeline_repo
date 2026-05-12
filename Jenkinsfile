pipeline {
    agent any

    stages {

        stage('STAGE 1') {
            steps {
                sh 'sleep 5'
                echo 'this is stage 1...'
            }
        }

        stage('STAGE 2') {
            steps {
                sh '''
                #!/bin/bash
                pwd
                ls -lrt
                sleep 5
                '''
                echo 'this is stage 2...'
            }
        }

        stage('STAGE 3') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}