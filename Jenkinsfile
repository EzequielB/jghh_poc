pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                echo 'Hello World!'
                echo sh(returnStdout: true, script: 'env')
            }
        }
    }

}
