@Library ('shared-library-nico@devel') _
def userInput

pipeline {
    agent any
    stages {
        stage('list branches') {
            steps {
                    userInput = inputBranches
            }
        }
    }
}
