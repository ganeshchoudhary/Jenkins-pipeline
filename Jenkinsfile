
pipeline{
  agent any
   tools {
        maven 'Maven 3.3.9'
        jdk 'jdk8'
    }
  stages{
    stage("Welcome"){
      steps{
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
