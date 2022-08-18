# pipedemo


pipiline {
     agent any
        stages{
            stage('build'){
                steps{
                     echo "Building the code.."    
                
                }
                
            }
            stages('test'){
                steps{
                    echo "testing the code.."
                }
                
            }
            stage('QA'){
                steps{
                    echo "QA analysis.."
                }
            }
            stage('Deploy'){
                steps{
                    echo "deploying the code.."
                }
            }
            stage('Monitor'){
                steps{
                    echo "Monitoring the code.."
                }
        }
    }
}
