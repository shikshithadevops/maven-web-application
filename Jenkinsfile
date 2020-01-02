node
{
 def mavenHome=tool name: "maven3.6.3"
 stage('Checkout')
 {
  git branch: 'development', credentialsId: 'f850b3ac-d4e3-4ae8-b9e3-6f67c7f17cbf', url: 'https://github.com/shikshithadevops/maven-web-application.git'
 }
 /*
 stage('Build')
 {
  sh "${mavenHome}/bin/mvn clean package"
 } 
 stage('ExecuteSonarqubeReport')
 {
  sh "${mavenHome}/bin/mvn sonar:sonar"
 }
 stage('UpdateArtifacttonexus')
 {
  sh "${mavenHome}/bin/mvn deploy"
 }
 stage('DeployApplicationintoTomcat')
 {
  sshagent(['dc0ff70a-d48b-45d8-abf8-a54cefbe1275'])
  {
 sh "scp -o StrictHostKeyChecking=no  target/maven-web-application.war ec2-user@13.235.0.68:/opt/apache-tomcat-9.0.30/webapps"

}
}
*/
}
