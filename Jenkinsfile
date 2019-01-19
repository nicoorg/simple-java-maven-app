@Library ('shared-library-nico@devel') _


pipeline {
    agent any
    stages {
        stage('list branches') {
            steps {
                script {
                    userInput = inputBranches
                }
            }
        }
    }
}
