@Library ('shared-library-nico@devel') _
def userInput = input(
    id: 'userInput', message: 'Let\'s promote?', parameters: [
    [$class: 'ChoiceParameterDefinition',
        choices: ['one' , 'two' , 'three'],
        description: 'dropdown',
        name: 'dropdown'
        ]
    ])

pipeline {
    agent any
    stages {
        stage('list branches') {
            steps {
                script {
                    userInput
                }
                echo ("Escoja una rama")
            }
        }
    }
}
