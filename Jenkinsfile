pipeline {
    agent any
    
    stages {
        stage('Test'){
            Step{
                echo "Helllo world"
            }
           }
        state('Build'){
            input {
                message = "Should we continue?"
            }
        }
        stage('deploy-on-test'){
            steps {
                echo 'Hello deploy-on-test'
            }
        }
        stage('deploy-on-prod'){
            steps {
                echo 'Hello deploy-on prod'
            }
        }
    }
}
