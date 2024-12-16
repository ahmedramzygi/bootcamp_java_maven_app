#!/usr/bin/env groovy

pipeline {
    agent any    
    stages {
        stage('build') {
            steps {
                script {
                    echo "Building the application from ${env.BRANCH_NAME}"
                }
            }
        }
        stage('test') {
            
            steps {
                script {
                    echo "Testing the application..."
                }
            }
    }
        stage('deploy') {
            steps {
                script {

                    echo "Deploying the application..."
                }
            }
        }
    }
}
