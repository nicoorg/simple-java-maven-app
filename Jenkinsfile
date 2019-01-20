@Library ('shared-library-nico@devel') _

def userInput

pipeline {
    agent any
    stages {
        script {
            userInput = inputBranches
        }
        stage('list branches') {
            steps {
                echo ("Escoja una rama")
            }
        }
    }
}
