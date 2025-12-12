pipeline {
    agent any

    environment {
        MY_CRED = credentials('MY_SECRETS')
    }

    stages {
        stage('Load_Credentials') {
            steps {
                echo "Hello World"
                echo "my username is : ${MY_CRED_USR}"
                echo "my password is : ${MY_CRED_PSW}"
            }
        }
    }
}
