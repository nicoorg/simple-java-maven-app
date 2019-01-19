@Library ('shared-library-nico@devel') _


pipeline {
    agent any
    stages {
        stage('list branches') {
            steps {
                script {
                    inputBranches.inputBox
                }
            }
        }
        stage('Get parameters from input') {
            steps {
                echo ("Env: "+userInput['env'])
                echo ("Target: "+userInput['target'])
            }
        }

    }
}
