pipeline{
  agent any
  stages{
    stage("Welcome"){
      steps{
        sh '''
        echo "Welcome dev branch "
        '''
        }
      }
    stage("build"){
      steps{
        sh 'npm install'
        }
      }
      }
}
