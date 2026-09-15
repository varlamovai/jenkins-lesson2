pipeline {
    agent any

    stages {
        stage('Checkout & Run') {
            steps {
                sh 'chmod +x test.sh'
                sh './test.sh'
            }
        }
        
        stage('System Info') {
            steps {
                echo '=== Checking Disk Space ==='
                sh 'df -h'
            }
        }
    }
}
