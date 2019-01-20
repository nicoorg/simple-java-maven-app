@Library ('shared-library-nico@devel') _

def userInput

pipeline {
    agent any
    stages {

        stage('list branches') {
            steps {
                script {
                    userInput = inputBranches
                }
                echo ("Escoja una rama")
            }
        }
    }
}
