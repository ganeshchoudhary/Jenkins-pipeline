pipeline {
    agent none
    stages {
        stage('ls') {
            agent any

            steps {
                sh 'ls'
            }
        }
        
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
