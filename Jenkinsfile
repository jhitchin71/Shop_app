pipeline {
    agent any
    parameters {
        booleanParam(name: 'Refresh',
                    defaultValue: false,
                    description: 'Read Jenkinsfile and exit.')
                    }
    stages {
        stage('Building') {
            steps {
                sh 'sudo apt install tree'
            }
        }
    }
 }
