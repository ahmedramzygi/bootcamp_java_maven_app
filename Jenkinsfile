#!/usr/bin/env groovy

pipeline {
    agent any    
    stages {
        stage('build') {
            steps {
                script {
                    echo "Building the application from ${env.GIT_URL}"
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
