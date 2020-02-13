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
                echo "${Project}"
                script{
                    switch(projectname = "${Project}") {            
                         case "Colearn": 
                            result = "coln"; 
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
                    echo result;
                    }
                }
        }
    }
}
