pipeline {
    agent any
    environment {
        name = "love U"
    }
    parameters{
        string(name: 'PERSON', defaultvalue: 'Mr. Jenkins', description: 'who should i say Hello 2 ?')
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
