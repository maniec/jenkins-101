#!/usr/bin/env groovy
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Build Step!'
                sh 'ls -alt'
            }
        }
        stage('Test') {
            steps {
                echo 'Test Step!'
                echo {env.BRANCH_NAME}
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy Step!'
                pwd()
            }
        }
    }
}