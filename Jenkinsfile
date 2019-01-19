@Library ('shared-library-nico') _
def userInput

pipeline {
    agent any
    stages {
        stage('list branches') {
            steps {
                script {
                    userInput = input_branches.input_box
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
