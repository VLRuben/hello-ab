pipeline {
    agent any
    
    options {
        timestamps()
        ansiColor("xterm")
    }

    stages {
            stage('EB CREATE') {
                steps {
                        withAWS(credentials: 'ruben-aws-credentials') {
                                sh '/home/sinensia/hello-eb eb create eb-devops-rubenvl_${BUILD_NUMBER}' 
                            }
                        }

                }
            }
    }                 