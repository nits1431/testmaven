node{
  stage('SCM Checkout'){
    git 'https://github.com/nits1431/testmaven'
  }
  stage('Compile Package'){
    def mvnHome = tool name: 'maven', type: 'maven'
    sh '${mvnHome}/bin/mvn package'
  }
}
