pipeline {
    agent none
    stages {
         stage('Back-end') {
            agent {
                docker { image 'docker' }
            }
            steps {
                sh 'docker build -f Dockerfile  -t test01 .'
            }
        }
    }
}
