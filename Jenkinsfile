pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "hello world"
                
                pullRequest.addLabel('Build Passing')
            }
        }
    }
}
