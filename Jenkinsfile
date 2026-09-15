pipeline {
    agent any
    stages {
        stage('Environment Check') {
            steps {
                echo "Running on node: ${env.NODE_NAME}"
                sh 'uname -a'
                sh 'docker --version'
            }
        }
        stage('Hello World') {
            steps {
                echo 'Jenkins setup verified successfully!'
            }
        }
    }
}
