#!groovy
/*
 * get short hand for project info
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
                            echo "oh"; 
                            break; 
                         case "US East (N. Virginia) - us-east-1": 
                            echo "va"; 
                            break; 
                         case "US West (N. California) - us-west-1": 
                            echo "ca"; 
                            break; 
                         case "US West (Oregon) - us-west-2": 
                            echo "or"; 
                            break; 
                         case "Asia Pacific (Hong Kong) - ap-east-1": 
                            echo "hk"; 
                            break;
                        case "Asia Pacific (Mumbai) - ap-south-1": 
                            echo "mb"; 
                            break;
                        case "Asia Pacific (Osaka-Local) - ap-northeast-3": 
                            echo "os"; 
                            break;
                        case "Asia Pacific (Seoul) - ap-northeast-2": 
                            echo "se"; 
                            break;
                        case "Asia Pacific (Singapore) - ap-southeast-1": 
                            echo "sd"; 
                            break;
                        case "Asia Pacific (Sydney) - ap-southeast-2": 
                            echo "sd"; 
                            break;
                        case "Asia Pacific (Tokyo) - ap-northeast-1": 
                            echo "tk"; 
                            break;
                        case "Canada (Central) - ca-central-1": 
                            echo "cn"; 
                            break;
                        case "Europe (Frankfurt) - eu-central-1": 
                            echo "ff"; 
                            break;
                        case "Europe (Ireland) - eu-west-1": 
                            echo "ie"; 
                            break;
                        case "Europe (London) - eu-west-2": 
                            echo "ld"; 
                            break;
                        case "Europe (Paris) - eu-west-3": 
                            echo "pr"; 
                            break;
                        case "Europe (Stockholm) - eu-north-1": 
                            echo "st"; 
                            break;
                        case "Middle East (Bahrain) - me-south-1": 
                            echo "bh"; 
                            break;
                        case "South America (São Paulo) - sa-east-1": 
                            echo "sp"; 
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
