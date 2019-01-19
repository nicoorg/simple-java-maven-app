@Library ('shared-library-nico') _
pipeline {
    agent any
    stages {
        stage('list branches') {
            steps {
                echo ("Will get a dropdown to use the branch")
                script {
                    input_branches
                }
            }
        }
        
    }
}
