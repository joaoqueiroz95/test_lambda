#!/usr/bin/groovy
pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                sh 'echo "Running the test"'
                sh './scripts/test.sh'
            }
        }
    }
}
