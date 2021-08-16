node{
   stage('SCM Checkout'){
        git 'https://github.com/saikumar30421/sample-maven-project' 
         }
   stage('Compile-Package'){
        def mvnHome = tool name: 'Maven', type: 'maven'
        sh "${mvnHome}/bin/mvn package"
        }
}
