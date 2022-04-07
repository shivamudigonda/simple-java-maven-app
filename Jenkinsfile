node {
stage('SCM-Checkout'){
git 'https://github.com/gitakbar/simple-java-maven-app' }
stage ('compile-package')
{ def mvnhome=tool name:'my maven',type: 'maven'
sh "${mvnhome}/bin/mvn clean install "
}
}
