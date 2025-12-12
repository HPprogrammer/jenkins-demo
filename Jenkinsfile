pipeline {
    agent any
    environment {
        name = "love U"
        MY_CRED = credentals('MY_SECRETS')
    }
   
    stages {
        stage('Load_Credentials') {
            steps {
                echo 'Hello World'
                echo 'my username is : $MY_CRED_USR'
                echo 'my password is : $MY_CRED_PSW'
                
            }
        }
    }
}
