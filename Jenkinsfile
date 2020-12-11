pipeline {
    agent none
    stages {
         stage('Back-end') {
            agent { dockerfile true }

            steps {
                sh '''
                echo "testing"
                '''
            }
        }
    }
}
