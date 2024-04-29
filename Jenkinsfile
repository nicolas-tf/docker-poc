pipeline {
    agent any

    stages {

        stage('Hello World') {
            steps {
                echo 'Hello World - ${env.BUILD_ID}'
            }
        }

        stage('How are you') {
            steps {
                echo 'How are you?'
            }
        }

        stage('Bye') {
            steps {
                echo 'Fine, tks!'
            }
        }
    }
}