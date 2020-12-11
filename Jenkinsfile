
pipeline{
  agent any
 
  stages{
    stage("Welcome"){
      steps{
        sh 'mvn --v'
        }
      }
     stage("build"){
      steps{
        sh 'mvn clean package'
        sh 'mvn clean install'
       
        }
      }
   
   
      stage("test"){
      steps{
       

        sh 'ls'
       
        }
      }
      }

}
