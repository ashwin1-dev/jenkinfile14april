pipeline {
    agent any
    
    tools {
          maven "jenkins-maven"
         }
    
    
    stages {
         stage('SCM') {
            steps {
                git 'https://github.com/ashwin1-dev/jenkinfile14april.git'
                 }
           }
        
        stage('Build') {
            steps {
                build  vlc2
             }
         }
        
        stage('Deploy') {
             steps {
                 sh "sudo cp                /usr/share/tomcat/webapps/"
                 }
            }
      }
}
