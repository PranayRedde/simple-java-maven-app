node {
stage('SCM-Checkout'){
git 'https://github.com/gitakbar/simple-java-maven-app' }
stage ('compile-package')
{ def mvnhome=tool name:'maven.01',type: 'maven'
sh "${mvnhome}/bin/mvn clean install "
}
}
