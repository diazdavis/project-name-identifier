#!groovy
/*
 * get congfiguartion values to a teraform
 */
pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Setting up short hand for project') {
            steps {
                step{
                    out << "Hello World"
                    }
                }
        }
    }
}
