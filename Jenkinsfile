pipeline {
    agent any

    stages {

        stage('Test') {
            steps {
                echo "Hello world"
            }
        }

        stage('Build') {
            steps {
                script {
                    input message: "Should we continue?"
                }
            }
        }

        stage('deploy-on-test') {
            steps {
                echo 'Hello deploy-on-test'
            }
        }

        stage('deploy-on-prod') {
            steps {
                echo 'Hello deploy-on-prod'
            }
        }
    }
}
