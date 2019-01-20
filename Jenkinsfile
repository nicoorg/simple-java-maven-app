@Library ('shared-library-nico@devel') _

def userInput

pipeline {
    agent any
    stages {
        stage('list branches') {
            script {
                userInput = inputBranches
            }
            steps {
                echo ("Escoja una rama")
            }
        }
    }
}
