#!/usr/bin/groovy
pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                sh 'echo "Running the test"'
                sh 'ls'
                sh 'chmod -x scripts/hello-world.sh'
                sh './scripts/hello-world.sh'
            }
        }
    }
}
