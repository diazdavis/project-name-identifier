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
                echo "${Project name}"
                script{
                    switch("${Project name}") {            
                         case "Colearn": 
                            echo "coln"; 
                            break; 
                         case "Perromart": 
                            echo "prmt"; 
                            break; 
                         case "klub": 
                            echo "klub"; 
                            break; 
                         case "USPL": 
                            echo "uspl"; 
                            break; 
                         case "Surge": 
                            echo "surg"; 
                            break;
                      }
                }
                }
        }
    }
}
