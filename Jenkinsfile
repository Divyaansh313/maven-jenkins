  pipeline{
    agent any
    stages{
      stage('Clean'){
          steps{
          echo 'Clean Stage'
          bat 'mvn -f C:/Users/ASUS/.jenkins/workspace/Final_Lab_exp/my-app clean'
          }
      }
      stage('Test'){
          steps{
          echo 'Testing stage'
          bat 'mvn -f C:/Users/ASUS/.jenkins/workspace/Final_Lab_exp/my-app test'
          }
      }
      stage('Install'){
          steps{
          bat 'mvn -f C:/Users/ASUS/.jenkins/workspace/Final_Lab_exp/my-app install'
          }
      }
    }
}
