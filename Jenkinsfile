pipeline {
    agent any
    
    options {
        timestamps()
        ansiColor("xterm")
    }

    stages {
            stage('EB CREATE') {
                steps {
                       dir("home/sinensia/hello-eb") {
                        sh 'eb create eb-devops-rubenvl_${BUILD_NUMBER}' 
                       }
                }
            }
    }
}                    