node{
  stage('SCM Checkout'){
    git 'https://github.com/nits1431/testmaven'
  }
  stage('Compile Package'){
    sh 'mvn package'
  }
}
