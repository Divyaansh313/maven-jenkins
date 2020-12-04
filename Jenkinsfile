  pipeline{
    agent any
    stages{
      stage('Clean'){
          steps{
          echo 'Clean Stage'
          bat 'mvn -f C:\Users\ASUS\.jenkins\workspace\Final_Lab_exp clean'
          }
      }
      stage('Test'){
          steps{
          echo 'Testing stage'
          bat 'mvn -f C:\Users\ASUS\.jenkins\workspace\Final_Lab_exp test'
          }
      }
      stage('Install'){
          steps{
          bat 'mvn -f C:\Users\ASUS\.jenkins\workspace\Final_Lab_exp install'
          }
      }
    }
}
