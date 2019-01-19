@Library ('shared-library-nico') _

def userInput = input(
    id: 'userInput', message: 'Let\'s promote?', parameters: [
    [$class: 'TextParameterDefinition', defaultValue: 'uat', description: 'Environment', name: 'env'],
    [$class: 'TextParameterDefinition', defaultValue: 'uat1', description: 'Target', name: 'target']
    ])

pipeline {
    agent any
    stages {
        stage('list branches') {
            steps {
                script {

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
