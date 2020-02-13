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
                script{
                    switch("${params.Project}") {            
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
                        default:
                            echo "wrong selection";
                            break;
                      }
                    }
                script{
                    switch("${params.Environment}") {            
                         case "Development": 
                            echo "dev"; 
                            break; 
                         case "Test": 
                            echo "tst"; 
                            break; 
                         case "Staging": 
                            echo "stg"; 
                            break; 
                         case "Production": 
                            echo "uspl"; 
                            break; 
                         case "Surge": 
                            echo "prd"; 
                            break;
                        case "Emergency (On demand)": 
                            echo "emg"; 
                            break;
                        default:
                            echo "wrong selection";
                            break;
                      }
                    }
                }
        }
    }
}
