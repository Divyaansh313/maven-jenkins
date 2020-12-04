  pipeline{
    agent any
    stages{
      stage('Build'){
          steps{
          echo 'Build Stage'
          bat 'mvn install'
          }
      }
      stage('Deploy'){
          steps{
          bat 'mvn deploy'
          }
      }
    }
}
