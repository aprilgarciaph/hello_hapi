#!/usr/bin/env groovy

pipeline {

    agent {
        docker {
            image 'node'
            args '-u root'
        }
    }

    stages {
        stage('Build') {
            steps {
                echo 'Build...'
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                echo 'Test...'
            }
        }
    }
}
