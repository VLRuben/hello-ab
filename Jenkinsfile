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
                                dir("eb-devops-ruben") {
                                    echo 'hola'
                                   
                                }       
                        }
                }
            }
    }
}                 
