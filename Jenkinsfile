node {
stage('SCM-Checkout'){
git 'https://github.com/shivamudigonda/simple-java-maven-app.git' }
stage ('compile-package')
{ def mvnhome=tool name:'mymaven',type: 'maven'
sh "${mvnhome}/bin/mvn clean install "
}
}
