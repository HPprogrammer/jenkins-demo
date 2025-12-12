pipeline {
    agent any
    environment {
        name = "love U"
    }
    parameters{
        string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
    }
    stages {
        stage('Step1') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Step2') {
            steps {
                echo "hello i realy $name"
                echo "my built with paremeter is $PERSON"
            }
        }
    }
}
