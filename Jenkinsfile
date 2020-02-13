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
                script{
                    switch("${params.Region}") {            
                         case "US East (Ohio) - us-east-2": 
                            echo "dev"; 
                            break; 
                         case "US East (N. Virginia) - us-east-1": 
                            echo "tst"; 
                            break; 
                         case "US West (N. California) - us-west-1": 
                            echo "stg"; 
                            break; 
                         case "US West (Oregon) - us-west-2": 
                            echo "uspl"; 
                            break; 
                         case "Asia Pacific (Hong Kong) - ap-east-1": 
                            echo "prd"; 
                            break;
                        case "Asia Pacific (Mumbai) - ap-south-1": 
                            echo "emg"; 
                            break;
                        case "Asia Pacific (Osaka-Local) - ap-northeast-3": 
                            echo "emg"; 
                            break;
                        case "Asia Pacific (Seoul) - ap-northeast-2": 
                            echo "emg"; 
                            break;
                        case "Asia Pacific (Osaka-Local) - ap-northeast-3": 
                            echo "emg"; 
                            break;
                        case "Asia Pacific (Singapore) - ap-southeast-1": 
                            echo "emg"; 
                            break;
                        case "Asia Pacific (Sydney) - ap-southeast-2": 
                            echo "emg"; 
                            break;
                        case "Asia Pacific (Tokyo) - ap-northeast-1": 
                            echo "emg"; 
                            break;
                        case "Canada (Central) - ca-central-1": 
                            echo "emg"; 
                            break;
                        case "Europe (Frankfurt) - eu-central-1": 
                            echo "emg"; 
                            break;
                        case "Europe (Ireland) - eu-west-1": 
                            echo "emg"; 
                            break;
                        case "Europe (London) - eu-west-2": 
                            echo "emg"; 
                            break;
                        case "Europe (Paris) - eu-west-3": 
                            echo "emg"; 
                            break;
                        case "Europe (Stockholm) - eu-north-1": 
                            echo "emg"; 
                            break;
                        case "Middle East (Bahrain) - me-south-1": 
                            echo "emg"; 
                            break;
                        case "South America (São Paulo) - sa-east-1": 
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
