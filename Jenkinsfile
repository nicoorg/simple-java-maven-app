@Library ('shared-library-nico') _
pipeline {
    agent any
    stages {
        stage('list branches') {
            steps {
                script {
                    def userInput = input(
 id: 'userInput', message: 'Let\'s promote?', parameters: [
 [$class: 'TextParameterDefinition', defaultValue: 'uat', description: 'Environment', name: 'env'],
 [$class: 'TextParameterDefinition', defaultValue: 'uat1', description: 'Target', name: 'target']
])

                }
            }
        }
        stage('Get parameters from input') {
            echo ("Env: "+userInput['env'])
            echo ("Target: "+userInput['target'])
        }

    }
}
