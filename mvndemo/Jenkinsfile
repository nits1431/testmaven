pipeline{
  agent any
  tools{
      maven 'maven'
  }
  stages{
        stage("GIT Checkout"){
            steps{
              git 'https://github.com/nits1431/testmaven'
            }
        }
        stage("Maven Build"){
            steps{
                bat 'mvn clean package'
            }
        }
    }
}
