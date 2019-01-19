@Library ('shared-library-nico') _



pipeline {
    agent any
    stages {
        stage('list branches') {
            steps {
                script {
                    input_branches
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
