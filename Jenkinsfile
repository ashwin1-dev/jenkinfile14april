pipeline {
    agent any
    
    tools {
          maven "jenkins-maven"
         }
    
    
    stages {
         stage('SCM') {
            steps {
                git 'https://github.com/ashwin1-dev/31-march-maven2.git'
                 }
           }
        
        stage('Build') {
            steps {
                sh "mvn  clean package"
             }
         }
        
        stage('Deploy') {
             steps {
                 sh "sudo cp  /var/lib/jenkins/workspace/pp-last/target/vlc2.war   /usr/share/tomcat/webapps/"
                 }
            }
      }
}
