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
                switch(${Name}) {            
                         case Colearn: 
                            println("coln"); 
                            break; 
                         case Perromart: 
                            println("prmt"); 
                            break; 
                         case klub: 
                            println("klub"); 
                            break; 
                         case USPL: 
                            println("uspl"); 
                            break; 
                         case Surge: 
                            println("surg"); 
                            break; 
                         default: 
                            println("The value is unknown"); 
                            break; 
                      }
                }
        }
    }
}
