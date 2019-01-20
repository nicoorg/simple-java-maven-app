@Library ('shared-library-nico@devel') _
def userInput = input(
    id: 'userInput', message: 'Let\'s promote?', parameters: [
    [$class: 'DropdownAutocompleteParameterDefinition',
        defaultValue: '1',
        description: 'dropdown',
        name: 'dropdown' ,
        dataProvider:
            [$class: 'SimpleTextProvider' ,
            autoCompleteData: 'one,two,three'
        ]
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
            }
        }
    }
}
