#!/usr/bin/env groovy

pipeline {
    agent any
    stages {
        stage('docker-compose up') {
            steps {
                sh 'docker-compose -f docker-compose.prod.yml up -d --build'
            }
        }
    }
}