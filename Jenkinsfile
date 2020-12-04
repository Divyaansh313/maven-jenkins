  pipeline{
    agent any
    stages{
      stage('Clean'){
          steps{
          echo 'Clean Stage'
          bat 'mvn clean'
          }
      }
      stage('Test'){
          steps{
          echo 'Testing stage'
          bat 'mvn test'
          }
      }
      stage('Install'){
          steps{
          bat 'mvn install'
          }
      }
    }
}
