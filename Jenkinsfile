pipeline {
    agent any
    environment {
        name = "love U"
    }
    parameters{
        string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
        choice(name: 'CHOICE', choices: ['Apply', 'Distroy'], description: 'Pick something')
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
                echo "My choice peremeter is $CHOICE"
            }
        }
    }
}
