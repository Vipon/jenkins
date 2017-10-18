#!/usr/bin/env groovy

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                g++ test.cpp -o test
            }
        }
        stage('Test') {
            steps {
                ./test
            }
        }
    }
}
