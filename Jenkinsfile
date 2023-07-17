#!/usr/bin/groovy
pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                sh 'echo "Running the test"'
                sh 'ls'
                sh 'chmod -x scripts/test.sh'
                sh './scripts/test.sh'
            }
        }
    }
}
